#
# CMake template for compiling more than one plugin
#
cmake_minimum_required(VERSION 3.15 FATAL_ERROR)

project(AllPlugins)

add_subdirectory(twoplugins)
add_subdirectory(sample)
