cmake_minimum_required(VERSION 3.30)
project(c_calculator)

set(CMAKE_CXX_STANDARD 14)

add_executable(c_calculator
    LICENSE
    README.md
        src/main.c
        include/calculator.h)
