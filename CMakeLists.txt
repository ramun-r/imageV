cmake_minimum_required(VERSION 3.16)
project(imageV LANGUAGES CXX)

SET(SOURCES
    src/main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})
