cmake_minimum_required(VERSION 3.0)

project(zoo)

add_library(zoo
    src/zoo.cpp
)

add_subdirectory(examples)

enable_testing()
add_subdirectory(tests)
