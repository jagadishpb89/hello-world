cmake_minimum_required(VERSION 2.9)

project(hello-world)

set( CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g -O0 -fprofile-arcs -ftest-coverage" )
set(CMAKE_C_OUTPUT_EXTENSION_REPLACE 1)
add_executable( sample Sample.c )

