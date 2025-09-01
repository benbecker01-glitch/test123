# setze CMake Version 3.0 voraus
cmake_minimum_required(VERSION 3.10)

# C++11 Standard verwenden
set(CMAKE_CXX_STANDARD 11)

# zusaetzliche Compiler-Optionen
add_compile_options(-O0 -pedantic -Wfatal-errors -Wall)
add_compile_options(-Wextra -Wshadow -Wconversion -Wno-unused)

# Projektname fuer CMake
project(Test123)

# die Liste aller ausfuehrbaren Programme
add_executable(hello-world main.cpp add.cpp)