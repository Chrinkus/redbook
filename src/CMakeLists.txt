add_executable(00-glfw		00-glfw.cpp)
target_link_libraries(00-glfw PRIVATE glfw OpenGL)

add_executable(01-triangles	01-triangles.cpp)
target_link_libraries(01-triangles PUBLIC glfw OpenGL::GL vermilion ${CMAKE_DL_LIBS})
