cmake_minimum_required(VERSION 2.6)
project(hello-world-cpp)
add_executable(hello-world-cpp main.cpp)
install(TARGETS hello-world-cpp DESTINATION bin)
