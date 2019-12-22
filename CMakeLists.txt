cmake_minimum_required(VERSION 3.0)
set(CMAKE_C_STANDARD 99)
project(GreenFFTs LANGUAGES C)

add_subdirectory( src )
add_subdirectory( tests )
