cmake_minimum_required(VERSION 3.8)
project(excel-automation)
SET(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} /subsystem:windows /ENTRY:mainCRTStartup")
add_executable(excel-automation WIN32 main.cpp)