# Set sample variable
SET(EXTERNAL_LIBS FMT wiringPi GMP)

cmake_minimum_required(VERSION 3.30)

# Project settings
project(Template-for-cpp LANGUAGE CXX)

# Set the C++ standard globally
set(CMAKE_CXX_STANDARD 20) 
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# Define the target executable
add_executable(template-project_main main.cpp)

# Link external libraries
# target_link_libraries(template-project_main PRIVATE ${EXTERNAL_LIBS})


