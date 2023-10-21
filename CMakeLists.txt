cmake_minimum_required(VERSION 3.20)
project(imgui)

set(CMAKE_CXX_STANDARD 20)

file(GLOB SOURCES "*.cpp" "*.h")

add_library(imgui ${SOURCES})

target_include_directories(imgui PUBLIC .)