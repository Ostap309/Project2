cmake_minimum_required(VERSION 3.10.0)
project(Stack)
enable_testing()
add_subdirectory(googletest)
add_executable(stack main.cpp emulator.cpp)
target_link_libraries(stack gtest_main gmock_main)