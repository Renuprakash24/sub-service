cmake_minimum_required(VERSION 3.16.3)

project(hello)

include_directories(${PROJECT_SOURCE_DIR}/include)

include_directories(${PROJECT_SOURCE_DIR}/Poco)


add_executable(app /root/.jenkins/workspace/cmake6/include/main.cpp)


