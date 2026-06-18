cmake_minimum_required(VERSION 3.16)

project(FootballGame)

set(CMAKE_CXX_STANDARD 17)

find_package(SDL2 REQUIRED)

add_executable(FootballGame
    src/main.cpp
)

target_link_libraries(FootballGame SDL2::SDL2)
