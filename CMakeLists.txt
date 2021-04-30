CMAKE_MINIMUM_REQUIRED(VERSION 2.7)
PROJECT(foc)
add_executable(foc main.c)

add_library(mylib STATIC mylib.c)
target_link_libraries(foc mylib m)
