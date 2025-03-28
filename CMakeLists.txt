cmake_minimum_required(VERSION 3.16)

project(ExampleProject VERSION 0.1.0 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)

add_executable(ExampleProject src/main.cpp)

find_package(spdlog CONFIG REQUIRED)
target_link_libraries(ExampleProject PRIVATE
    spdlog::spdlog
)
