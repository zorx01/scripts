# ROS 2 Humble Setup with Docker

This repository contains the necessary setup scripts and Docker configuration for setting up a ROS 2 Humble environment, along with a setup script for a manipulator. Follow the instructions below to get started.

## Table of Contents

- [Dockerfile](#dockerfile)
- [ROS 2 Humble Setup Script](#ros-2-humble-setup-script)
- [Manipulator Setup Script](#manipulator-setup-script)
- [Additional Setup Script (Placeholder)](#additional-setup-script-placeholder)

## Dockerfile

This Dockerfile sets up a ROS 2 Humble environment with CUDA support. You can build and run the Docker container using the following commands:

```bash
# Build the Docker image
docker build -t ros2_humble:latest .

# Run the Docker container
docker run -it --rm ros2_humble:latest
