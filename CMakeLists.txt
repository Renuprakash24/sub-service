cmake_minimum_required(VERSION 3.16.3)

project(hello)

include_directories(${poco-sub/Poco/Poco})

add_executable(app /root/.jenkins/workspace/cmake6/include/main.cpp)
