cmake_minimum_required(VERSION 3.23)

project(sqlite-backend LANGUAGES CXX C)

add_executable(sqlite-backend 
    app/src/main.cpp 
    sqlite3/src/sqlite3.c 
)
