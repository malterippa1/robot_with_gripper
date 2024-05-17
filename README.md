# Intro

This repository combines the UR10e robot arm with the Robotiq 2F 85 Gripper.

# How to use this thing

Make sure to install https://github.com/UniversalRobots/Universal_Robots_ROS2_Description (Universal Robots/Universal_Robots_ROS2_Description). Additional dependencies may need to be installed.

The gripper can be obtained by installing https://github.com/PickNikRobotics/robotiq_85_gripper PickNikRobotics/robotiq_85_gripper.

# Run it
Use ros2 launch robot_with_gripper view_ur.lauch.py to simulate the robot in RViz only.
Use ros2 launch robot_with_gripper gazebo.lauch.py to simulate the robot in RViz and Gazebo.