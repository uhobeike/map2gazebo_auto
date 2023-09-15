cmake_minimum_required(VERSION 3.8)
project(map2gazebo_auto)

find_package(ament_cmake_auto REQUIRED)

ament_auto_package(
INSTALL_TO_PATH
  scripts
INSTALL_TO_SHARE
  config
  launch
)
