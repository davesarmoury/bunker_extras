cmake_minimum_required(VERSION 3.0.2)
project(bunker_viz)

find_package(catkin REQUIRED COMPONENTS)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES bunker_viz
#  CATKIN_DEPENDS joint_state_publisher_gui robot_state_publisher rviz
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
