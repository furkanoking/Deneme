cmake_minimum_required(VERSION 3.10)

project(Myproject)
set(SOURCES src/furkan.cpp)

include_directories(include)

add_executable(my_program ${SOURCES})