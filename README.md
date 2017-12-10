# Run freespace simulation in Turtlebot Stage

## Description

This is a tutorial for running the freespace simulation in Turtlebot Stage. The simulation demonstrates how to convert a freespace image to point cloud in ROS, how to overlay it to the costmap in Navigation Stack.

## Preparation

- Copy the package source files of `freespace_conversion`, `segnet_ros`, `turtlebot_navigation` and `turtlebot_stage` to ROS workspace `~/catkin_ws/src`

- Build the workspace by

  ```c
  cd ~/catkin_ws
  catkin_make
  ```

## Testing

- Run the ROS launch file

  ```c
  roslaunch turtlebot_stage freespace_in_blank_stage.launch
  ```
