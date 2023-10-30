cmake_minimum_required(VERSION 3.16.3)

project(
        MyFirstHelloWorldCMake
        VERSION 1.0.0
        DESCRIPTION "Простий демонстративний проект з використанням CMake і С++"
        HOMEPAGE_URL http://www.kytok.org.ua/post/cmake-lehkyj-start
        LANGUAGES CXX
)

add_executable(MyFirstHelloWorldCMake src/main.cpp)
