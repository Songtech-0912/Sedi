cmake_minimum_required(VERSION 3.7)

project(SDL2-Textedit)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${PROJECT_SOURCE_DIR}/cmake")
find_package(SDL2 REQUIRED)
find_package(SDL2_ttf REQUIRED)
include_directories(${SDL2_INCLUDE_DIRS} ${SDL2_TTF_INCLUDE_DIRS})

add_executable(SDL2-Textedit main.cpp)
target_link_libraries(SDL2-Textedit ${SDL2_LIBRARIES} ${SDL2_TTF_LIBRARIES})

file(COPY font.ttf DESTINATION ${CMAKE_BINARY_DIR})
