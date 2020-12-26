cmake_minimum_required(VERSION 3.16)

project(redbook-vermilion VERSION 0.1 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(OpenGL REQUIRED)

include_directories(include)

add_subdirectory(src)
