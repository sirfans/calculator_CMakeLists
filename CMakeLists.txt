cmake_minimum_required(VERSION 3.0)

project(calc C)

include_directories(inc)

set(SOURCES
        src/calcu.c
        src/add.c
        src/sub.c
        src/mul.c
        src/div.c
)

set(HEADERS
        inc/calcu.h
)

add_executable(calc ${SOURCES} ${HEADERS})
