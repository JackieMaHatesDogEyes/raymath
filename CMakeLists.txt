cmake_minimum_required(VERSION 3.0)

project(raymath)

add_library(raymath STATIC
    raymath.h
    raymath.c
)

# compile with fpic

set_target_properties(raymath PROPERTIES
    POSITION_INDEPENDENT_CODE ON
)