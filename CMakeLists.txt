cmake_minimum_required(VERSION 3.7)
project(FreeStore)

set(CMAKE_CXX_STANDARD 11)

include_directories(header)

set(SOURCE_FILES header/Resource.h src/Resource.cpp src/FreeStore.cpp src/Memory.cpp src/Person.cpp header/Person.h)
add_executable(FreeStore ${SOURCE_FILES})