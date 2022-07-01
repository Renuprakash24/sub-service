cmake_minimum_required(VERSION 3.16.3)

project(hello)

include_directories(hi /root/.jenkins/workspace/cmake6/poco/Poco)


add_executable(app /root/.jenkins/workspace/cmake6/include/main.cpp)

target_link_libraries( hi app)
