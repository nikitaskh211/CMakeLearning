# setting up minimal requirements -- subdirectories, includes
cmake_minimum_required(VERSION 3.10)

# project naming
project(helloWorld)

# custom message
message("[ROOT] CMake script.")

# an include finder
include_directories(lib/inc)

# a subdirectory
add_subdirectory(lib)
add_subdirectory(src)
