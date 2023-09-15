cmake_minimum_required(VERSION 3.8)
project(map2gazebo_auto)

find_package(ament_cmake_auto REQUIRED)

ament_auto_package(
INSTALL_TO_PATH
  scripts/map2gazebo_docker.sh
  scripts/output_check.sh
INSTALL_TO_SHARE
  config
  launch
)
