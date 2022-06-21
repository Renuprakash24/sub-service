
include(cmake/platform.cmake)



add_subdirectory(${platform_SOURCE_DIR}/app ${platform_BINARY_DIR})
add_subdirectory(${hal_SOURCE_DIR}/lib ${hal_BINARY_DIR})
