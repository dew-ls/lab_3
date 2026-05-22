project(formatter)
add_library(formatter STATIC formatter.cpp formatter.h)
target_include_directories(formatter INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
