cmake_minimum_required(VERSION 3.14)
project(bbpp-solver)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories("include")
add_library(bbpp-solver src/bbpp-solver.cpp)
