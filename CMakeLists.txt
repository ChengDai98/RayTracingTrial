cmake_minimum_required(VERSION 3.8)

project(RayTracyingExample)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} ${PROJECT_SOURCE_DIR}/src/main.cpp)
include_directories(${PROJECT_NAME} ${PROJECT_SOURCE_DIR}/include)