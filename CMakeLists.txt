cmake_minimum_required(VERSION 3.15)
project(Louvain)

set(CMAKE_CXX_STANDARD 14)

include_directories(source)

add_executable(Louvain
        source/main.cpp
        source/main.h)
