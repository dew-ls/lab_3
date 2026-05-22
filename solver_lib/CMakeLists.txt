project(solver)
add_library(solver STATIC solver.cpp solver.h)
target_include_directories(solver INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
