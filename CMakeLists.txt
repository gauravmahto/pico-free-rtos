cmake_minimum_required(VERSION 3.12)

include(pico_sdk_import.cmake)

project(Pico-FreeRTOS)

pico_sdk_init()

add_subdirectory(free-rtos)
add_subdirectory(project-files)
