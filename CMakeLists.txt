cmake_minimum_required(VERSION 2.6)
project(shortest_path)

add_compile_options(-std=c++11)

include_directories(include)

add_executable(Dijkstra Dijkstra.cpp main_Dijkstra.cpp)

add_executable(Floyd Floyd.cpp main_Floyd.cpp)



