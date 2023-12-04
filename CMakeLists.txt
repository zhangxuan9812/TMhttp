cmake_minimum_required(VERSION 3.26)
project(TMhttp)

set(CMAKE_CXX_STANDARD 17)

#include_directories(.)
include_directories(src)

add_executable(TMhttp src/server.h src/TEST.cpp)
