# spot
In this repositpry, I'll simulate the working of Boston Dynamic's famous quadruped, Spot Mini, in ROS. 
The .stl files have been taken from http://www.thingiverse.com/thing:3445283

# setting up the package 
```bash
cd catkin_ws/src
git clone https://github.com/prithvi-poddar/spot.git
cd ..
catkin_make
```

# visualizing in rviz
To visualize the robot in rviz, enter the following in terminal
```bash
roslaunch spot spot.launch
```
You need to set the "Fixed Frame" field under the "Displays" section to 'body'. 
A gui will also open up to move the various joints of the robot.

# future work
Final gazebo simulations with navigation will soon be uploaded.
