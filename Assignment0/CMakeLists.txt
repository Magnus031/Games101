cmake_minimum_required(VERSION 3.2)
project (Transformation)

#find_package(Eigen3 REQUIRED)
#include_directories(EIGEN3_INCLUDE_DIR)
include_directories(./../)

#include_directories("/opt/homebrew/Cellar/eigen/3.4.0_1/include/")

add_executable (Transformation main.cpp)
