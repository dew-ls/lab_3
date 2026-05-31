cmake_minimum_required(VERSION 3.11)
project(solver_pkg)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(formatter_lib)
add_subdirectory(formatter_ex_lib)
add_subdirectory(hello_world_application)
add_subdirectory(solver_lib)
add_subdirectory(solver_application)

set(SOLVER_VERSION 1.0.0)

include(CPackConfig.cmake)
