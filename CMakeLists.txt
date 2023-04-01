cmake_minimum_required(VERSION 3.15)
project(Neuron VERSION 0.1)

# Add .lib files
link_directories(${CMAKE_SOURCE_DIR}/lib)

# Include header files
include_directories(
    include/headers
    include/glm
)

# Add all source files
file(GLOB SOURCES "src/*.cpp")
add_executable(Neuron ${SOURCES})
