cmake_minimum_required(VERSION 3.10)

# Set the project name
project(HelloWorld)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(hello main.cpp)

# Specify installation rules
install(TARGETS hello DESTINATION /usr/bin)
