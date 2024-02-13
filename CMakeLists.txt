cmake_minimum_required(VERSION 3.26)
project(Paral_DZ)

set(CMAKE_CXX_STANDARD 17)

option(USE_DOUBLE "use double instead of float" OFF)

if(USE_DOUBLE)
    add_executable(sinus main.cpp)
    target_compile_definitions(sinus PRIVATE ARRAY_TYPE=double)
else()
    add_executable(sinus main.cpp)
    target_compile_definitions(sinus PRIVATE ARRAY_TYPE=float)
endif()
