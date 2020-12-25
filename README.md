# TurtleBot-Path-Tracking-using-PID-Controller
This Node created can be used for turtlebot control of single and mutli point navigation. For which further we can determine steering angle at each instant of time. 

# Results:

Results testing with Kp =0.5, Kd =0.01, Ki=0.0001
<p float="center">
<img src="animations/PID_control.gif" width="49%"/>
</p>

Results testing on mutli goal points
<p float="center">
<img src="animations/PID_control.gif" width="49%"/>
</p>

Results with multi-goal points
<p float="center">
<img src="animations/Multiple_goals.gif" width="49%"/>
</p>



# Lauching simulation

First download the repo and create a catkin workspace

```
 roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```

Once gazebo is launched, open another terminal, then

```
source ./devel/setup.bash
```
```
rosrun turtlebot3_controller controller_node
```

# References:

Create Catkin_ws and initialize it, Follow the http://wiki.ros.org/ROS/Tutorials link for more information.

Install tutlebot3 package, Follow the https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/ link for more information.


