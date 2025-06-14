cmake_minimum_required(VERSION 3.29)
project(80BitFloat)

set(CMAKE_CXX_STANDARD 23)

add_executable(80BitFloat main.cpp
        CustomFloat.h)
