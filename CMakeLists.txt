cmake_minimum_required( VERSION 3.16 )

project( multimethod )

set( CMAKE_CXX_STANDARD 20 ) # But c++11 is required by task

add_executable( multimethod
    src/main.cpp src/multimethod.hpp src/shape.cpp src/shape.hpp
)