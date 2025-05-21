cmake_minimum_required(VERSION 3.23)
project(mujocox)

set(CMAKE_CXX_STANDARD 17)

# Options
add_subdirectory(third_party/mujoco)

add_subdirectory(testing)
