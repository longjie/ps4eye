cmake_minimum_required(VERSION 2.8.3)
project(ps4eye)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch script camera_info
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  USE_SOURCE_PERMISSIONS)

install(FILES 91-ps4eye.rules
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
