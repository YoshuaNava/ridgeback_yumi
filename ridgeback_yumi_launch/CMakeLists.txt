cmake_minimum_required(VERSION 2.8.3)
project(ridgeback_yumi_launch)

find_package(catkin REQUIRED COMPONENTS roslaunch)

catkin_package()

roslaunch_add_file_check(launch/gazebo_pos_control.launch)
roslaunch_add_file_check(launch/gazebo_vel_control.launch)

roslaunch_add_file_check(launch/gazebo_vel_control.launch)

