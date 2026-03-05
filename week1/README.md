# Week 1 ROS2 Lab

## Description
In this lab we installed ROS2 and created our first ROS2 Python package called my_first_pkg.

## Commands Used

Check ROS2 version:
ros2 --version

Create workspace:
mkdir -p ~/ros2_ws/src

Create package:
ros2 pkg create my_first_pkg --build-type ament_python --dependencies rclpy

Build workspace:
colcon build

Source workspace:
source install/setup.bash

Run node:
ros2 run my_first_pkg hello_node

## Problems Faced
Initially colcon build failed due to missing dependencies. I solved it by cleaning the workspace and rebuilding it.

## Reflection
This lab helped me understand the basic structure of ROS2. I learned how to create a workspace, build packages, and run a simple Python node. I also learned how ROS2 commands work in the terminal. This lab gave me hands-on experience with ROS2 and helped me understand how packages and nodes are organized.
