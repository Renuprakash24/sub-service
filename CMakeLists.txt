cmake_minimum_required(VERSION 3.16.3)

project(cmake)




include(FetchContent)


FetchContent_Declare(
    platform
    GIT_REPOSITORY  https://github.com/Renuprakash24/poco_repo.git
    GIT_TAG   main
    CONFIGURE_COMMAND   ""
    BUILD_COMMAND       ""
    
)


FetchContent_GetProperties(platform)
if(NOT depname_POPULATED)

  FetchContent_Populate(platform)

 
 

  
  add_subdirectory(${platform_SOURCE_DIR} ${platform_BINARY_DIR})
endif()
