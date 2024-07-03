cmake_minimum_required(VERSION 3.12)
project(ysm_cpp_libs)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_CXX_FLAGS_DEBUG "{CMAKE_CXX_FLAGS_DEBUG} -g")
set(CMAKE_CXX_FLAGS_RELEASE "{CMAKE_CXX_FLAGS_RELEASE} -O2")

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY {PROJECT_BINARY_DIR}/bin)

add_subdirectory(memory_allocator)