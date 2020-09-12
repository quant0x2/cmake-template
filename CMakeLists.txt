cmake_minimum_required(VERSION 3.10)

project(cmakeTemplate VERSION 0.1 LANGUAGES CXX)

add_executable(main ./src/main.cpp ./src/message.cpp)
target_include_directories(main PRIVATE include)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
