cmake_minimum_required(VERSION 3.0)

project(basicsocket)

add_executable(basicsocket main.cpp)

install(TARGETS basicsocket RUNTIME DESTINATION bin)
