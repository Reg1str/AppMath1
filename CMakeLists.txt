cmake_minimum_required(VERSION 3.21)
project(lab_1)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(lab_1
        main.cpp
        constants.h
        methods.h

        Dichotomy.cpp
        GoldenRatio.cpp
        Fibonacci.cpp
        Parabola.cpp
        Brent.cpp

        objectiveFunction.cpp
        fibonacciNumberFunction.cpp
        )
