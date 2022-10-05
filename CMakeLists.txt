cmake_minimum_required(VERSION 3.23)
project(badCode C)

set(CMAKE_C_STANDARD 11)

add_executable(badCode
        main.c calculate.h)
