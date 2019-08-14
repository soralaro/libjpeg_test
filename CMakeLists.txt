cmake_minimum_required(VERSION 3.12)
project(libjpeg_test)

set(CMAKE_CXX_STANDARD 14)
link_directories(${CMAKE_SOURCE_DIR}/)
add_executable(libjpeg_test main.cpp)
target_link_libraries(libjpeg_test PRIVATE -lturbojpeg)