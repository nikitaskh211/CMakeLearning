# setting up minimal requirements -- custom message
cmake_minimum_required(VERSION 3.10)

# project naming
project(helloWorld)

# custom message
message("DEBUG COMMANDS")

# addition of the exec file
add_executable(main hello.cpp main.cpp)
