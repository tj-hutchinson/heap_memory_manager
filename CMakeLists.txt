cmake_minimum_required(VERSION 3.23)
project(heap_memory_manager C)

set(CMAKE_C_STANDARD 11)

add_executable(heap_memory_manager main.c mm.h uapi_mm.h)
