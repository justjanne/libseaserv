cmake_minimum_required(VERSION 3.10)
project(libseaserv VERSION 13.0.0 LANGUAGES C)

find_package(Python3 REQUIRED COMPONENTS Interpreter)

add_subdirectory(src/seafile)
add_subdirectory(src/seaserv)
