cmake_minimum_required(VERSION 2.8.3)
project(rpg_calib)

# search for everything we need to build the messages, dont forget the message_generation
find_package(catkin REQUIRED COMPONENTS
)

# export the dependencis of this package for who ever depends on us
catkin_package(
CATKIN_DEPENDS
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

