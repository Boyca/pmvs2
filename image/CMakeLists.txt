cmake_minimum_required(VERSION 2.6)
project(pmvs2)

set(image_SRCS image.cc)
add_library(image SHARED ${image_SRCS})
