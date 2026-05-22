project(solver_app)
add_library(solver_app STATIC equation.cpp)
target_link_libraries(solver_app PRIVATE formatter_ex solver)
