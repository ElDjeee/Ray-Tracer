cmake_minimum_required(VERSION 3.10)
project(RTProject VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file(GLOB SRC_FILES *.cc *.cpp)

add_executable(RTProject ${SRC_FILES})
