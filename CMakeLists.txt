cmake_minimum_required(VERSION 3.10)

set(CMAKE_CXX_COMPILER clang++-18)
set(CMAKE_C_COMPILER clang-18)

project(hello_world)
set(CMAKE_CXX_STANDARD 20)

add_executable(hello_world src/main.cpp)