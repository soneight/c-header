cmake_minimum_required(VERSION 3.8)

project(c-header VERSION 0.1.0 LANGUAGES C)
# project private properties
add_subdirectory(source)
# project public properties
target_include_directories(${PROJECT_NAME} INTERFACE include)
