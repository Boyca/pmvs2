cmake_minimum_required(VERSION 2.6)
project(pmvs2)
set(CMAKE_VERBOSE_MAKEFILE on)
add_subdirectory(pmvs)
add_subdirectory(numeric)
add_subdirectory(image)
add_executable(pmvs2 pmvs2.cc)

