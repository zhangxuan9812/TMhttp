cmake_minimum_required(VERSION 3.26)
project(TMhttp)

set(CMAKE_CXX_STANDARD 17)

#include_directories(.)
include_directories(src)
include_directories(SQLConnect)
include_directories(/usr/local/include/)
include_directories(/opt/homebrew/Cellar/mysql-client/8.2.0/include)
add_executable(TMhttp src/server.h src/TEST.cpp
        SQLConnect/sql_connect.h
        SQLConnect/sql_connect.cpp)
