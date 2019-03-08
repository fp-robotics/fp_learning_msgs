cmake_minimum_required(VERSION 2.8.3)
project(fp_learning_msgs)

# find message_generation library
find_package(catkin REQUIRED
  message_generation
)

# generate services in the 'srv' folder
add_service_files(
  FILES
  RecognizeObject.srv
)

# generate added messages and services
generate_messages()

