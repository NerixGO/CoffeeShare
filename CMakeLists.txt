cmake_minimum_required(VERSION 3.28)
project(CoffeeShare VERSION 0.1.0 LANGUAGES CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(coffeeshare apps/coffeeshare/main.cpp)
target_compile_features(coffeeshare PRIVATE cxx_std_20)