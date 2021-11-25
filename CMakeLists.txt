cmake_minimum_required(VERSION 3.9)

project(libyuarel VERSION 0.1)

add_library(${PROJECT_NAME} STATIC
    yuarel.c
)

target_include_directories(${PROJECT_NAME} PUBLIC .)
