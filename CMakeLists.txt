cmake_minimum_required(VERSION 2.8)
project(a2-ece650)

set (CMAKE_CXX_FLAGS "-std=c++11 -Wall ${CMAKE_CXX_FLAGS}")

add_executable(a2-ece650 a2-ece650.cpp parser.hpp parser.cpp edge.hpp edge.cpp graph.hpp graph.cpp)

