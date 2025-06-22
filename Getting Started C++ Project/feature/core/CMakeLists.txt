# Add the library
add_library(Library STATIC
    src/Math.cpp
)

target_include_directories(Library
    PUBLIC
        ${CMAKE_SOURCE_DIR}/feature/core/inc
)

