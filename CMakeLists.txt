cmake_minimum_required(VERSION 3.10)
project(HelloCI)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(include)

add_library(hello STATIC src/hello.cpp)
add_executable(main src/main.cpp)
target_link_libraries(main PRIVATE hello)