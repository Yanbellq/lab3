cmake_minimum_required(VERSION 3.27)
project(lab3)

set(CMAKE_CXX_STANDARD 23)

add_executable(lab3 main.cpp
        bikeConfig.cpp
        client.cpp
        employer.cpp
        operator.cpp
        operator.h)
