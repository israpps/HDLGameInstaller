cmake_minimum_required(VERSION 3.10)

# set the project name
project(HDLGManClient)

# add the executable
#include_directories(include)

add_executable(HDLGManClient
    "client.c"
    "HDLGManClient.c"
    "install-main.c"
    "io.c"
    "iso9660.c"
    "main.c"
    "OSD.c"
    "system.c"
)