cmake_minimum_required(VERSION 3.16)
project(tech_scout_match_processing)

set(CMAKE_CXX_STANDARD 14)

find_package(OpenCV REQUIRED)

add_executable(tech_scout_match_processing main.cpp)

target_link_libraries(tech_scout_match_processing ${OpenCV_LIBS})
