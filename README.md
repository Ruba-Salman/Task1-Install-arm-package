# Task1-Install-arm-package
This task is for installing and operating the arm package on ROS.
Steps taken to solve this task:
Created a workspace for catkin
Open the terminal on Ubuntu.
I typed these commands:
$ source /opt/ros/melodic/setup.bash
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
After that I wrote the commands for added the arduino robot arm package to “src” folder.
I installed all other commands.
I added the source file of the setup.bash file to bashrc file.
I updated the source of bashrc file.
I wrote this command to launch the application: $ roslaunch robot_arm_pkg check_motors.launch
Finally the Riviz application work and I can control the arm from it.
