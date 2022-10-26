cmake_minimum_required(VERSION 3.23)
project(PP_Prima_algorithm)

set(CMAKE_CXX_STANDARD 14)

add_executable(PP_Prima_algorithm main.cpp sequence.cpp sequence.h)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}   -fopenmp")