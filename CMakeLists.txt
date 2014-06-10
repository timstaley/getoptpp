cmake_minimum_required(VERSION 2.8)
project(getoptpp) 

file(GLOB getoptpp_headers getoptpp/*.h)

include_directories( ${CMAKE_CURRENT_SOURCE_DIR})

set(sources src/getopt_pp.cpp)

add_library(getoptpp ${sources})
