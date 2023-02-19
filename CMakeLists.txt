cmake_minimum_required(VERSION 3.0.2)
project(my_robot_description)


find_package(catkin REQUIRED COMPONENTS
  joint_state_publisher_gui
  robot_state_publisher
  urdf
)

catkin_package()
include_directories(${catkin_INCLUDE_DIRS})

