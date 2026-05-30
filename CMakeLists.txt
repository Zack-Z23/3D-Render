cmake_minimum_required(VERSION 4.2)
project(CPP_Project)

set(CMAKE_CXX_STANDARD 20)

add_executable(CPP_Project main.cpp
        vec3.h
        color.h
        ray.h
        hittable.h
        sphere.h)
