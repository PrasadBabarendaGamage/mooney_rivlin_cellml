set(ExampleName "mooney_rivlin_cellml")

cmake_minimum_required(VERSION 3.4 FATAL_ERROR)
project(${ExampleName} VERSION 1.0.0 LANGUAGES C Fortran)

find_package(OpenCMISSLibs 1.3.0 COMPONENTS iron REQUIRED CONFIG)

add_subdirectory(src/fortran)
