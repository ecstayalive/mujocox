add_executable(test_mujoco test_mujoco.cpp)
target_link_libraries(test_mujoco PRIVATE mujoco)

add_executable(test_object test_object.cpp)
target_link_libraries(test_object PRIVATE mujoco)
