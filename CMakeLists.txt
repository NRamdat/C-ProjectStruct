# cmake project autoRC
cmake_minimum_required(VERSION 3.1 FATAL_ERROR)
project(C++ProjectStruct) # change name for every project

# setup compiler
add_compile_options(-std=c++17 -Ofast -Wall -Wextra)


add_executable(run
        main.cpp
        )
target_link_libraries(run)