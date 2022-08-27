cmake_minimum_required(VERSION 3.23)
project(yoptac C CXX)

set(CMAKE_C_STANDARD 99)

include_directories(include)

add_executable(yoptac_c_test1   test/c/test1.c)
add_executable(yoptac_cpp_test1 test/cpp/test1.cpp)