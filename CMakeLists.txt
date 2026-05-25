cmake_minimum_required(VERSION 3.23)
project(KR_TCPL LANGUAGES C)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
add_compile_options(-Wall -Wextra -Wpedantic)

add_subdirectory(src)
