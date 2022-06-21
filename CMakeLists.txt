  cmake_minimum_required(VERSION 3.16.3)

include(cmake/platform.cmake)



add_subdirectory(${platform_SOURCE_DIR}/Poco ${platform_BINARY_DIR})
