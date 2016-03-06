cmake_minimum_required(VERSION 2.8.3)
project(myzharbot_control)

find_package(catkin REQUIRED COMPONENTS roslaunch)

catkin_package()

roslaunch_add_file_check(launch)


