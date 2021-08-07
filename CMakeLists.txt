cmake_minimum_required(VERSION 3.10)

project(GAMES102)

if(NOT CMAKE_BUILD_TYPE)
	message(STATUS "No build type selected, default to Release")
	set(CMAKE_BUILD_TYPE "Release")
endif()

include_directories(./extern/eigen-3.3.7)

add_subdirectory(extern)
add_subdirectory(Lesson01)