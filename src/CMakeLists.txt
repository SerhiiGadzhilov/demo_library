cmake_minimum_required(VERSION 3.4)

# Project Name
project(DemoLibrary)

# Generate shared librarry libdemo
add_library(demo SHARED demo.cpp)