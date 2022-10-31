cmake_minimum_required(VERSION 3.23)
project(data_structure C)

set(CMAKE_C_STANDARD 99)

add_executable(data_structure main.c)

add_executable(1-2 introduction/1-2.c)
add_executable(1-3 introduction/1-3.c)
add_executable(Single-LinkedList linear-list/LinkedList/Single-LinkedList.c)
add_executable(SqList linear-list/SqList/SqList.c)
add_executable(2-5 linear-list/2-5.c)
add_executable(e1-1 experiment/e1-1.c)
add_executable(3-2 stacks-and-queues/3-2.c)
add_executable(3-3 stacks-and-queues/3-3.c)
add_executable(3-4 stacks-and-queues/3-4.c)
add_executable(e2-1 experiment/e2-1.c)
add_executable(3-5 stacks-and-queues/3-5.c)
add_executable(2-6 linear-list/2-6.c)