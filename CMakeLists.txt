cmake_minimum_required(VERSION 3.0.0)
project(OpenGL VERSION 0.1.0)

file (GLOB SRC ${CMAKE_SOURCE_DIR}/src/*.cpp)

add_executable(OpenGL ${SRC})