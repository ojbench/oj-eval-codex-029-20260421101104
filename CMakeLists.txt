cmake_minimum_required(VERSION 3.10)
project(problem_029 C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_C_EXTENSIONS OFF)

add_executable(code main.c)
target_compile_options(code PRIVATE -O2 -pipe -static -s)

