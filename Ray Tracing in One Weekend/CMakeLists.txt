cmake_minimum_required(VERSION 3.10)
project(RayTracing)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(raytracer src/main.cpp)
