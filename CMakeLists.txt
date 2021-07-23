cmake_minimum_required(VERSION 3.16)

project(
    Test
    VERSION 0.0.1
    LANGUAGES C CXX
)

# Use a pkg-config module for cmake
#find_package(PkgConfig)

# define GNU standard installation directories 
include(GNUInstallDirs)

# C++ compile flags
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(src)