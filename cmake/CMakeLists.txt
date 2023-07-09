cmake_minimum_required(VERSION 3.16)
project(hello)
set(CMAKE_CXX_STANDARD 11)
add_compile_options(-Wall -Wextra)

add_executable(hello hello.cpp)

