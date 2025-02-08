# setting up minimal requirements -- subdirectories, includes
cmake_minimum_required(VERSION 3.10)

# project naming
project(helloWorld)

# assigning a variable which puts our output into a binary folder
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${PROJECT_SOURCE_DIR}/bin")

# custom message
message("[ROOT] CMake script.")

# an include finder
include_directories(lib/inc)

# a subdirectory
add_subdirectory(lib)
add_subdirectory(src)
