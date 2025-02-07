# setting up minimal requirements
cmake_minimum_required(VERSION 3.10)

# project naming
project(helloWorld)

# addition of the exec file
add_executable(
  main
  hello.cpp
  main.cpp
)
