# adafruit_imu
ROS driver for Adafruit 9-DOF IMU Breakout - L3GD20H + LSM303

This ros package provides a ros node that publishes Imu and MagneticField type messages to "imu" and "mag" topics respectively when the IMU is connected to I2C interface on board. Tested on Raspberry Pi 2 Model B V1.1 aka 2B+

This repo is forked from https://github.com/rolling-robot/adafruit_imu, and adapted for my IMU model and ROS topics. Initially this code is adapted using work of tuuzdu: https://github.com/tuuzdu/crab_project
