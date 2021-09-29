cmake_minimum_required(VERSION 3.20)
project(dulling)

set(CMAKE_CXX_STANDARD 17)

add_library(dulling library.cpp md5.cpp md5.h)
