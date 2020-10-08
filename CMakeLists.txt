cmake_minimum_required(VERSION 3.13.0)
project (benchmark LANGUAGES C)
 
add_executable(test-arm_sve test-arm_sve.c)
install(TARGETS test-arm_sve DESTINATION ${CMAKE_INSTALL_BINDIR} COMPONENT test-arm_sve)
