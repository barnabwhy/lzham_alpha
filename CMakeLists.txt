# PROJECT(lzham)
cmake_minimum_required(VERSION 2.8)
option(BUILD_X64 "build 64-bit" TRUE)

if( WIN32 )
    add_definitions( -DWIN32 )
endif()

add_subdirectory(lzhamdecomp)
add_subdirectory(lzhamcomp)
add_subdirectory(lzhamdll)
