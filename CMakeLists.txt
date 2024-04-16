cmake_minimum_required(VERSION 3.27)
project(my_Algorithm)

set(CMAKE_CXX_STANDARD 17)

add_executable(my_Algorithm main.cpp
        String/recursion.cpp
        String/recursion.h
        String/not_recursion.cpp
        String/not_recursion.h)
