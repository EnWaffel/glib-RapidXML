cmake_minimum_required(VERSION 3.5)

project(RapidXML LANGUAGES CXX VERSION 1.0.0)

file(GLOB_RECURSE SRC RapidXML/*.cpp)

add_library(RapidXML STATIC ${SRC})