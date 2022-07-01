cmake_minimum_required(VERSION 3.16.3)

project(hello)






add_executable(app /root/.jenkins/workspace/cmake6/include/main.cpp)

target_include_directories(my_lib PUBLIC /root/.jenkins/workspace/cmake6/poco/Poco)



