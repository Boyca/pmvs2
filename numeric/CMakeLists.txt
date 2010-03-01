cmake_minimum_required(VERSION 2.6)
project(pmvs2)

set(numeric_SRCS mylapack.cc)
add_library(numeric SHARED ${numeric_SRCS})
