cmake_minimum_required(VERSION 3.15)
project(Neuron)

include_directories(include/headers)

# Add all source files
file(GLOB SOURCES "src/*.cpp")
add_executable(Neuron ${SOURCES})
