cmake_minimum_required(VERSION 3.10.2)
project(robot_with_gripper)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY
    config
    launch
    urdf
  DESTINATION
    share/${PROJECT_NAME}
)

ament_package()
