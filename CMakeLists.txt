cmake_minimum_required(VERSION 3.7)
project(LinkedLists)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp src/LinkedList.cpp LinkedList.h src/Node.cpp Node.h)
add_executable(LinkedLists ${SOURCE_FILES})