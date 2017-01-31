cmake_minimum_required(VERSION 2.8.9)
project (CMakeHelloWorld)

#version number
set (CMakeHelloWorld_VERSION_MAJOR 1)
set (CMakeHelloWorld_VERSION_MINOR 0)

add_executable(CMakeHelloWorld helloworld.cpp)

install (TARGETS CMakeHelloWorld DESTINATION bin)