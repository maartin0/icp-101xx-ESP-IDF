cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "icp101xx.cpp" "icp101xx.h"
                       INCLUDE_DIRS "."
                       REQUIRES arduino)

project(icp-101xx)