cmake_minimum_required(VERSION 3.16)

project(redbook VERSION 0.1 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_compile_options(-Wall -Wextra -Wpedantic)

include_directories(include)
link_directories(lib)

add_subdirectory(src)
