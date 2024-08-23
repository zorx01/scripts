# ROS 2 Humble Setup with Docker

This repository contains the necessary setup scripts and Docker configuration for setting up a ROS 2 Humble environment, along with a setup script for a manipulator. Follow the instructions below to get started.

## Table of Contents

- [Dockerfile](# Dockerfile)
- [ROS 2 Humble Setup Script](# ROS2 humble Script)
- [Manipulator Setup Script](# Manipulator setup script)

## Dockerfile

This Dockerfile sets up a ROS 2 Humble environment with CUDA support. You can build and run the Docker container using the following commands:

```bash
# Build the Docker image
~
```

```bash
# Run the Docker container
~
```

## ROS2 humble Script

This script will install ros2 humble in your system.

```bash
# Download the script
curl -OL https://raw.githubusercontent.com/nandu-k01/scripts/main/setup_humble.sh
```

```bash
# Run the script
chmod +x setup_humble.sh
./robotic_arm_setup.sh

```

## Manipulator setup script

This script will create a ros2 workspace of the doosan_arm manipulator from here https://github.com/nandu-k01/robotic_arm_environment

```bash
# Download the script
curl -OL https://raw.githubusercontent.com/nandu-k01/robotic_arm_environment/main/robotic_arm_setup.sh
```

```bash
# Run the script
chmod +x robotic_arm_setup.sh
./robotic_arm_setup.sh

```

