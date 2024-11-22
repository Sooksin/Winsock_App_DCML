cmake_minimum_required(VERSION 3.29)
project(server_app)

set(CMAKE_CXX_STANDARD 20)

link_libraries(ws2_32 wsock32)

add_executable(server_app main.cpp)
