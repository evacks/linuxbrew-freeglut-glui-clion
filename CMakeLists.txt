cmake_minimum_required(VERSION 3.28)
project(projectname)

set(CMAKE_CXX_STANDARD 17)
set(OpenGlLinkers -lglut -lGLU -lGL)

add_executable(projectname main.cpp)
target_link_libraries(projectname ${OpenGlLinkers})

