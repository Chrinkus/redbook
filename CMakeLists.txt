cmake_minimum_required(VERSION 3.16)

project(redbook VERSION 0.1 LANGUAGES CXX C)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_compile_options(-Wall -Wextra -Wpedantic)

find_package(OpenGL REQUIRED)

include_directories(include)
include_directories(lib/vermilion/include)
link_directories(lib/vermilion/build/src)

add_subdirectory(src)
