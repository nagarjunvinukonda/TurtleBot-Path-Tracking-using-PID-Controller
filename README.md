# TurtleBot-Path-Tracking-using-PID-Controller
# Overview
The package is used for determining steering angle at each instant of time. Here the user flexibility for selecting single or multi-goal point control system. This package is tested both on simulation and hardware setup as shown below. The aim of this project is to develop a path tracking system for turtlebot. 

# Results:
<!--
Results testing with Kp =0.5, Kd =0.01, Ki=0.0001
-->
Turtlebot PID controller results:
<p float="center">
<img src="animations/PID_control.gif" width="49%"/>
</p>

Results with multi-goal points
<p float="center">
<img src="animations/multi_goal_points.gif" width="49%" height = "49%"/>
</p>



# Lauching simulation

First create a catkin workspace and download the repo

```
 roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```

Once gazebo is launched, open another terminal, then

```
source ./devel/setup.bash
```
```
rosrun pid_controller pid_controller
```

# References:

Create Catkin_ws and initialize it, Follow the http://wiki.ros.org/ROS/Tutorials link for more information.

Install tutlebot3 package, Follow the https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/ link for more information.


