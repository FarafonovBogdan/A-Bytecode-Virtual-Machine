cmake_minimum_required(VERSION 3.10)
project(MyWasmVM C)

set(CMAKE_C_STANDARD 99)

# Добавляем все исходные файлы
add_executable(myprogram main.c chunk.c memory.c debug.c)
