cmake_minimum_required(VERSION 3.2)

project(learnopengl)

# find_package(glfw3 REQUIRED)
add_subdirectory("libs/glfw")


add_executable(learnopengl src/main.cpp)
target_link_libraries(learnopengl glfw)
