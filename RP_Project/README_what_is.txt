# ROS project
Implementation of Teleoperation, Localization and Trajectory planning node in ROS for a 4 wheeled robot using C++.

Functinons:
- Teleoperation of a Robot in a map world defined in Webots using ROS nodes for sensor enabling
- Implementation of a localization node to correlate the transfer functions of different frames
- Application of the ROS gmapping node to populate a static global map of the world using the laser scan of the Lidar
- Configuration of the move_base ROS node, to apply a global and local path planning using the lidar in order to reach different goals 
