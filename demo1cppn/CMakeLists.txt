cmake_minimum_required(VERSION 3.4.1)

PROJECT(demo1cpp)

aux_source_directory(. DIR_SRCS)

add_library(javanativelib SHARED ${DIR_SRCS})

target_link_libraries(javanativelib log)


 