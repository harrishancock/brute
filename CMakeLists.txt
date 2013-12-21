# Barobo Root Build
# Barobo, Inc.

cmake_minimum_required(VERSION 2.8.9)

add_subdirectory(libsfp)
add_subdirectory(libbarobo)
add_subdirectory(BaroboLink)
add_subdirectory(BaroboLabHack EXCLUDE_FROM_ALL)
