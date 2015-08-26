cmake_minimum_required (VERSION 2.6)

set(PROJECT template)

set(HEADRES ../inc/test.h)

set(SOURCES ../src/main.cpp ../src/hello.cpp)

project(${PROJECT})

include_directories (../inc)

source_group ("Header Files" FILES ${HEADERS})

source_group ("Source Files" FILES ${SOURCES})

add_executable(${PROJECT} ${HEADRES} ${SOURCES})
