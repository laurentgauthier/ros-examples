cmake_minimum_required(VERSION 2.8.3)
project(example_srvs)

find_package(catkin REQUIRED COMPONENTS message_generation)

add_service_files(DIRECTORY srv
  FILES
  AddTwoInts.srv)

generate_messages()

catkin_package(CATKIN_DEPENDS message_runtime)
