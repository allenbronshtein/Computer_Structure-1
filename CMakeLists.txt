cmake_minimum_required(VERSION 3.15)
project(ex1 C)

set(CMAKE_C_STANDARD 99)

add_executable(ex1 main.c bytes.c bytes.h main.c)