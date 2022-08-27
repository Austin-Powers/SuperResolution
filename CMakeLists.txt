cmake_minimum_required(VERSION 3.14)

project(SuperResolution VERSION 1.0)

include(THzCommon/cmake/helper_functions.cmake)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(THzCommon)
add_subdirectory(THzImage)
