cmake_minimum_required(VERSION 3.17)
project(effectivec C)

set(CMAKE_C_STANDARD 11)

add_executable(effectivec main.c test.c types.c)