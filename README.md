# ROS2 Sensor Pipeline

AMR (Autonomous Mobile Robot) sensor data management system built in modern C++, designed for ROS2 integration.

## About
This project is part of my journey to become a robotics software engineer.
It implements core data structures used in real robot sensor pipelines,
starting from low-level C++ and building up to full ROS2 + CoppeliaSim integration.

## Tech Stack
- Modern C++ (C++11,Templates)
- ROS2 Jazzy (rclcpp)
- CoppeliaSim (coming soon)

## Project Roadmap
- [x] Phase 1 — SensorBuffer (Rule of Five, operator overloading)
- [x] Phase 2 — Battery Monitor (comparisons, move semantics)
- [ ] Phase 3 — RingBuffer<T> (templates, circular buffer)
- [ ] Phase 4 — SensorFusion (inheritance, composition)
- [ ] Phase 5 — ROS2 Node integration
- [ ] Phase 6 — CoppeliaSim simulation

## Concepts Covered
- Copy and Move constructors
- Operator overloading
- Templates
- Modern C++ memory management
- ROS2 publisher/subscriber nodes

