cmake_minimum_required(VERSION 3.22)
project(SameBoy)

set(CMAKE_CXX_STANDARD 17)

include_directories(source)

add_executable(${PROJECT_NAME}
        source/main.cpp)

target_link_libraries(${PROJECT_NAME} SDL3)
