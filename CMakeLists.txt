cmake_minimum_required(VERSION 3.5.0)
project(Rasterizer VERSION 0.1.0 LANGUAGES C CXX)

add_executable(Rasterizer 
main.cpp
tgaimage.cpp
tgaimage.h
)

