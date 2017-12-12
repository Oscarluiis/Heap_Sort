cmake_minimum_required(VERSION 3.8)
project(HeapSort_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Heap.cpp
        Heap.h
        main.cpp)

add_executable(HeapSort_master ${SOURCE_FILES})