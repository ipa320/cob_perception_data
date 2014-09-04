cmake_minimum_required(VERSION 2.4.6)
project(cob_tesseract_data)
find_package(catkin REQUIRED)
catkin_package()

#############
## Install ##
#############
install(DIRECTORY tessdata
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  PATTERN ".svn" EXCLUDE
)

