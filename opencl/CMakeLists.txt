cmake_minimum_required(VERSION 3.14)

find_package(OpenCL CONFIG REQUIRED COMPONENTS Headers OpenCL)

add_subdirectory(opencl-aot)
