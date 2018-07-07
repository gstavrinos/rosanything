cmake_minimum_required(VERSION 2.8.3)
project(rosanything)
find_package(catkin REQUIRED COMPONENTS
  rosbash
)
catkin_package()
include_directories(
  ${catkin_INCLUDE_DIRS}
)
