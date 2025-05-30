cmake_minimum_required(VERSION 3.10)
project(ImageRenderer)

# Set the C++ standard to at least 11 for your code
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add the executable
add_executable(render main.cpp)
