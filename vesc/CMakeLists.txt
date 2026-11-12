cmake_minimum_required(VERSION 3.5)
project(vesc)
find_package(ament_cmake_auto REQUIRED)

# Does not compile anything but needs to present to silence the warning
if(CMAKE_EXPORT_COMPILE_COMMANDS)
endif()

ament_auto_package()
