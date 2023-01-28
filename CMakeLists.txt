cmake_minimum_required(VERSION 3.24)
project(LLP2_Gremlin C)

set(CMAKE_C_STANDARD 11)

include_directories(include)
include_directories(include/stools)

add_executable(LLP2_Gremlin main.c src/stools/string_tools.c)
