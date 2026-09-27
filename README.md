# UEH_Vo-Thi-Anh-Thu
# UEH CRC 2026 – Simulation Round

**Name:** [YOUR FULL NAME]  
**School:** University of Economics Ho Chi Minh City (UEH)  
**Faculty:** School of Technology and Design  

## Project

**Vision-Based Autonomous Navigation and Control of TurtleBot3 Waffle Using ROS 2**

This project implements an autonomous navigation system for the
TurtleBot3 Waffle in the UEH CRC 2026 Simulation Round.

The system uses camera, LiDAR, and wheel odometry data for real-time
perception and control. The main components include lane detection,
traffic-event handling, FSM, and PD-based motion control.

## Environment

- ROS 2 Humble
- Gazebo Classic 11
- TurtleBot3 Waffle
- Python
- OpenCV

## ROS 2 Topics

- `/camera/image_raw` – Camera image
- `/scan` – LiDAR data
- `/odom` – Wheel odometry
- `/cmd_vel` – Robot velocity command

## Main Features

- Vision-based lane detection
- HSV image processing
- Polynomial lane fitting
- Traffic sign detection
- LiDAR-based obstacle detection
- Finite State Machine (FSM)
- PD-based lane tracking
- Dynamic velocity control

## Run

Start the simulation using the provided UEH CRC 2026 simulation pack.

After the simulator is running, execute:

```bash
ros2 run crc_sim starter
