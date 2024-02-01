cmake_minimum_required(VERSION 3.27)
project(Interpret)

set(CMAKE_CXX_STANDARD 17)

add_executable(TestCoverage main.cpp
        expr.cpp cmdline.cpp TESTS.cpp)
