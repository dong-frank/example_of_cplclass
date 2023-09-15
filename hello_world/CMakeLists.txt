cmake_minimum_required(VERSION 3.26) #最低版本
project(untitled C)

set(CMAKE_C_STANDARD 17) #标准

add_executable(untitled
        hello.c
        cmake-build-debug/.cmake/guessing.c)
#gcc hello.c -o hello