cmake_minimum_required(VERSION 3.15)

project(h264bitstream LANGUAGES C)

add_library(h264bitstream)

target_sources(h264bitstream PRIVATE h264_stream.c h264_sei.c h264_nal.c)