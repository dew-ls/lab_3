project(solver_app)
add_evecutable(solver_app equation.cpp)
target_link_libraries(solver_app PRIVATE formatter_ex solver)
install(TARGET solver_app DESTINATION bin)
