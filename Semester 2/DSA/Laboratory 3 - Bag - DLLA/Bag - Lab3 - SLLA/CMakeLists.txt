cmake_minimum_required(VERSION 3.25)
project(Bag___Lab3___SLLA)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Bag___Lab3___SLLA
        App.cpp
        Bag.cpp
        Bag.h
        BagIterator.cpp
        BagIterator.h
        ExtendedTest.cpp
        ExtendedTest.h
        ShortTest.cpp
        ShortTest.h)
