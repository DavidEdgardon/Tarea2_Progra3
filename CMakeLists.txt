cmake_minimum_required(VERSION 3.7)
project(TareaC2)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES cmake-build-debug/Evaluador.cpp cmake-build-debug/Evaluador.h cmake-build-debug/Main.cpp)
add_executable(TareaC2 ${SOURCE_FILES})