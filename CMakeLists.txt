cmake_minimum_required(VERSION 3.10.2)
project(robot_with_gripper)

find_package(catkin REQUIRED)

install(
  DIRECTORY
    config
    launch
    urdf
    rviz
  DESTINATION
    share/${PROJECT_NAME}
)

catkin_package()
