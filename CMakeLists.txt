cmake_minimum_required(VERSION 3.8)
project(Lexical_Analyzer_C)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c structures.h)
add_executable(Lexical_Analyzer_C ${SOURCE_FILES})