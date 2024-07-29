cmake_minimum_required(VERSION 3.28)
project(BobBuilder)

set(CMAKE_CXX_STANDARD 17)

add_executable(BobBuilder main.cpp
        src/func.cpp
        include/func.h)
