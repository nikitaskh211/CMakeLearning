# custom message
message("[SRC] CMake script.")

# addition of the exec file
add_executable(main main.cpp)

# linking libraries to the executable
target_link_libraries(main helloC)
