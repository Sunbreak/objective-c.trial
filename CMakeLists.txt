cmake_minimum_required(VERSION 3.16)
project(HelloWorld)

enable_language(OBJCXX)

add_executable(HelloWorld main.m)

target_link_libraries(HelloWorld
    "-framework Foundation"
)