cmake_minimum_required(VERSION 3.1)
project(9cc)
file(GLOB SOURCES
  src/main.cpp
  )
add_executable(${PROJECT_NAME} ${SOURCES})
add_definitions("-std=c++17")
add_definitions("-Wall")
add_definitions("-Wextra")
add_definitions("-g")
