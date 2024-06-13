# minimum require
cmake_minimum_required (VERSION 3.8.1)

# global solution
project(qtimgui_sln)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

# goto subs
add_subdirectory(examples)
add_subdirectory(modules)
add_subdirectory(src)
