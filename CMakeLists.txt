cmake_minimum_required(VERSION 3.5)

project(Capture LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Capture main.cpp)

install(TARGETS Capture
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
