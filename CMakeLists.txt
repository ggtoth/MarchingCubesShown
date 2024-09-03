cmake_minimum_required(VERSION 3.28)
project(CubesShow)

find_package(FreeGLUT)

set(CMAKE_CXX_STANDARD 17)

add_executable(CubesShow main.cpp)
target_link_libraries(CubesShow FreeGLUT::freeglut_static)
