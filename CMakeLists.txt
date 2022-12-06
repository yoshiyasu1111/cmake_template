cmake_minimum_required(VERSION 3.18)

project(hello)

message("Top level CMakeLists.txt")

add_executable(hello src/hello.cpp)
