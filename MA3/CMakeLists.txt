cmake_minimum_required(VERSION 3.23)
project(MA3)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_BUILD_TYPE Debug)

add_executable(MA3 main.cpp TwitterData.hpp TwitterData.cpp)
