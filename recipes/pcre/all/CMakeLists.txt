CMAKE_MINIMUM_REQUIRED(VERSION 2.8.11)
project(cmake_wrapper)

message(STATUS "Conan CMake Wrapper")
include(conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory("source_subfolder")
