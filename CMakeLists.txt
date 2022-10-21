cmake_minimum_required(VERSION 2.8.3)
project(detectron2_ros)

find_package(catkin REQUIRED COMPONENTS
  rospy
  message_generation
  std_msgs
  sensor_msgs
)

catkin_package(
  CATKIN_DEPENDS std_msgs sensor_msgs)