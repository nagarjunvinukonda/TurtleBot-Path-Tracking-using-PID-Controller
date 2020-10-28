# TurtleBot-Path-Tracking-using-PID-Controller
This Node created can be used for turtlebot control of single and mutli point navigation. Which for further we can determine steering angle at each instant of time. 

# Steps for Package installation

1) Create Catkin_ws and initialize it, Follow the http://wiki.ros.org/ROS/Tutorials link for more information.
2) install tutlebot3 package, Follow the https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/ link for more information.
3) Add pid node in scripts folder
4) make changes in launch file or create a launch file:
      <!-- The pid node -->
  <node name="pid" type="pid" pkg="tutlebot_package_name"/>
  
5) catkin_make
6) source/devel/setup.bash
7) roslaunch turtlebot
8) rosrun our node
