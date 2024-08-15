cmake_minimum_required(VERSION 3.28)
project(Redis_2nd_try)

set(CMAKE_CXX_STANDARD 17)

add_executable(Redis_2nd_try server.cpp
        client.cpp)
