cmake_minimum_required(VERSION 3.24)
project(Proyect1)

include_directories(lib)
include_directories(src)
include_directories(test)

include_subdirectory(lib/googleTest)
include_subdirectory(src)
include_subdirectory(test)

set(CMAKE_CXX_STANDARD 17)

add_executable(Proyect1 main.cpp src/Hospedaje.cpp src/Hospedaje.h)
