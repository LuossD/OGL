cmake_minimum_required(VERSION 3.21)
project(learn)

set(CMAKE_CXX_STANDARD 17)
link_libraries(glfw3 pthread dl X11)
add_executable(learn src/main.cpp)
add_executable(first src/first.cpp deps/glad.c)


