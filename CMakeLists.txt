cmake_minimum_required(VERSION 3.24)
project(obfuscator)

set(CMAKE_CXX_STANDARD 23)

add_executable(main.cpp pe/pe.cpp pe/pe.h)
