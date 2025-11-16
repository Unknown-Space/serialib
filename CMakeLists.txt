cmake_minimum_required(VERSION 3.22)
project(serialib)

set(CMAKE_CXX_STANDARD 17)

add_library(serialib
        lib/serialib.cpp
        include/serialib.h)

target_include_directories(serialib PUBLIC include)
