cmake_minimum_required(VERSION 2.6)
project(this_is)
add_executable(this_is main.c)
install(TARGETS this_is DESTINATION bin)
