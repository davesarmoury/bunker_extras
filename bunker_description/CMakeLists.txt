cmake_minimum_required(VERSION 3.0.2)
project(bunker_description)

find_package(catkin REQUIRED COMPONENTS)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES bunker_description
#  CATKIN_DEPENDS robot_state_publisher urdf xacro
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
