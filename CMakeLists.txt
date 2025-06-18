cmake_minimum_required(VERSION 3.10)
project(projectIdeaGenerator C)

find_package(cJSON CONFIG REQUIRED)
find_package(CURL REQUIRED)

add_executable(a.out src/main.c)

target_link_libraries(a.out PRIVATE cjson)

