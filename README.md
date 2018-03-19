# fontys_minor_ar_ros_a2

This repository contains files for assignment 2 of the ROS course that is part of the Fontys Minor 'Adaptive Robotics'.

## Installing the *fontys_minor_ar_ros_a2* package into your work space:

- Navigate to the src folder of your *catkin workspace* (default name catkin_ws):
```
  cd ~/catkin_ws/src
```  
- Clone the *fontys_minor_ar_ros_a2* files to your workspace using *git*:
```
  git clone https://github.com/KrisPiters/fontys_minor_ar_ros_a2.git
```  
## Contents

The package contains:

- A world file for stage, preconfigured with an empty map and a turtlebot
- An rviz configuration file, preconfigured for this assignment. (you can use the *2D Nav Goal* tool to directly publish goals to the */goal* topic)
- Launch files, these launch files already contain a general structure for use with *stage* and a *turtlebot*. They still need to be modified to include your own *servoing* and *point and shoot* nodes.

## Usage

Create a *src* folder for your nodes.

Modify the following launch files to include a reference to your nodes:

**For use with stage:**
- pointshoot_stage.launch
- servoing_stage.launch 

**For use with turtlebot:**
- pointshoot_turtlebot.launch
- servoing_turtlebot.launch


