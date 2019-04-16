cmake_minimum_required(VERSION 3.6)
project(kilo C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Wextra -pedantic -std=c99")
add_executable(kilo kilo.c)