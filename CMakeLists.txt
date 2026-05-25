cmake_minimum_required(VERSION 3.28)

project(ray-tracing-one-weekend)

set(EXEC inOneWeekend)

set(CMAKE_CXX_STANDARD 14)

file(GLOB SOURCES src/*.cc)

add_executable(${EXEC} ${SOURCES})