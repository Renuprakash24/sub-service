cmake_minimum_required(VERSION 3.16.3)

project(hello_world)

add_executable(app include/Can_main.cpp)
target_include_directories(app PUBLIC Poco)
