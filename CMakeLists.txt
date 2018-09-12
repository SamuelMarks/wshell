cmake_minimum_required(VERSION 3.12)
project(wshell)

set(CMAKE_C_STANDARD 11)

add_executable(wshell.c type_prompt.c read_command.c builtin_command.c parsing.c)
