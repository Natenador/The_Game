cmake_minimum_required(VERSION 3.5.1)

project(The_Game)

# VERSION
set(The_Game_VERSION_MAJOR 0)
set(The_Game_VERSION_MINOR 0)
set(The_Game_PATCH_VERSION 0)

set(CMAKE_CXX_COMPILER "g++")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17 -Wall")


set(SOURCE
    main.cpp
)


add_executable(The_Game ${SOURCE})
