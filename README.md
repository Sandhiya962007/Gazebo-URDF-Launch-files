# Gazebo-URDF-Launch-files

# Differential Drive Robot – ROS 2 & Gazebo

## Overview
This project describes a two-wheel differential-drive mobile robot using URDF (Unified Robot Description Format). The robot model is designed for visualization in RViz and simulation in Gazebo.

## Robot Components
- **Base Link:** Rectangular robot chassis (0.6 × 0.4 × 0.2 m).
- **Left and Right Wheels:** Continuous joints for wheel rotation.
- **Caster Wheel:** Spherical support wheel for stability.
- **LiDAR Sensor:** Mounted on the front of the robot.
- **Base Footprint:** Reference frame at the robot's ground level.

## Technologies Used
- ROS 2
- URDF (XML)
- Gazebo
- RViz 2

## Robot Control
The Gazebo differential-drive plugin controls the robot using the `cmd_vel` topic and publishes odometry on the `odom` topic. Wheel transforms and joint states can also be published by the plugin.

## Features
- Three-dimensional robot model
- Defined visual, collision, and inertial properties
- Configurable materials and colors
- Differential-drive movement
- Gazebo simulation support

## Purpose
The project provides a basic mobile robot model for learning robot modeling, simulation, movement control, and future integration of LiDAR-based navigation.# Differential Drive Robot – ROS 2 & Gazebo


- Gazebo simulation support

## Purpose
The project provides a basic mobile robot model for learning robot modeling, simulation, movement control, and future integration of LiDAR-based navigation.
