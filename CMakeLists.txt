cmake_minimum_required(VERSION 3.9)

project(cmake-test)

set(HEADERS "include/header.hpp")
set(COMMON_SRC "src/source.cpp")

add_library(objects OBJECT ${COMMON_SRC})
add_subdirectory(src)
add_subdirectory(test)
