cmake_minimum_required (VERSION 3.1)
project (${PROJECT_NAME} C)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

file(GLOB csourses *.c)
add_executable(${PROJECT_NAME} ${csourses})

