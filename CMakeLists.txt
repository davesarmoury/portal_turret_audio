cmake_minimum_required(VERSION 3.0.2)
project(turret_audio)

find_package(catkin REQUIRED)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES turret_audio
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

include_directories(
# include
# ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY launch audio
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
