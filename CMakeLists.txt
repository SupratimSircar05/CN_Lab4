cmake_minimum_required(VERSION 3.15)
project(CN_Lab4 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)


add_executable(CN_Lab4_Q1_c  Q1client.c)
add_executable(CN_Lab4_Q1_s  Q1server.c)
add_executable(CN_Lab4_Q2_c  Q2client.c)
add_executable(CN_Lab4_Q2_s  Q2server.c)
