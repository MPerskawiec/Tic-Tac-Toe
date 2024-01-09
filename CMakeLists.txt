cmake_minimum_required(VERSION 3.14)
project(TicTacToe)

set (SRC main.cpp gra.cpp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} ${SRC})