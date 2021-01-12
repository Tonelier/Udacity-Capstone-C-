cmake_minimum_required(VERSION 3.7)

add_definitions(-std=c++17)

set(CXX_FLAGS "-Wall")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")

project(FruityStore)

add_executable(FruityStore src/main.cpp src/input_validation.h src/input_validation.cpp src/output.h src/output.cpp)
