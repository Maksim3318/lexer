cmake_minimum_required(VERSION 3.17)
project(lexer)

set(CMAKE_CXX_STANDARD 20)

add_executable(lexer
        lexer_test.cpp
        lexer.h
        lexer.cpp
        test_runner.h)