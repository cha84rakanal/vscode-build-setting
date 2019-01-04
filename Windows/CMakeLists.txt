cmake_minimum_required(VERSION 3.1)

# -std= option
#set(CMAKE_CXX_STANDARD 14)

if(WIN32)
    # for Windows operating system in general
endif()

if(APPLE)
    # for MacOS X or iOS, watchOS, tvOS (since 3.10.3)
endif()

#set c++ flags
#set(CMAKE_CXX_FLAGS "")

#set include directories
#include_directories(./)

add_executable(a *.cpp)