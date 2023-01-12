cmake_minimum_required(VERSION 3.24)
SET(LIBHELLO_SRC hello.cpp)

ADD_LIBRARY(hello SHARED ${LIBHELLO_SRC})

