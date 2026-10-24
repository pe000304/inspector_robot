# inspector_robot

Hardware:
1) Slamtec RPLIDAR A1M8 - cheep standart ROS-robot. Cost 100y.e., distance 12 meters, frequancy 10 Hz, support in ROS2 drivers. Pro-versions - (for example, RPLIDAR A2, A3 or S3).
2) UVC (USB Video Class). For example, module OV5648 5MP. Stereolabs ZED или Intel RealSense). Note: code work abstract topic /camera/image_raw. We change driver camera, a hihg-level code (for example - detction objects) no change.
3) Ulta-sensor - HC-SR04 - libgazebo_ros_ray_sensor.so
4) Phyzics platforms - Hiwonder 4WD или LGDXRobot2. (For example open project LGDXRobot2)
5) Raspberry PI4
6) Arduino/ESP32

Software:
1) Linorobot2
2) [ROS 2 Humble.](https://docs.ros.org/en/humble/index.html). [Add install instructions](https://habr.com/ru/articles/768048/).
3) micro-ROS
4) Gazebo
