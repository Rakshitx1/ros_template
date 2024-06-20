# Robot Package Template

Welcome to the Robot Package Template! This template serves as a starting point for creating and developing robotics projects using ROS (Robot Operating System).

## Getting Started

To get started with this template, follow these steps:

1. **Creating a Workspace**: Create a new workspace directory and navigate into the `src` directory.
   ```bash
   mkdir -p ~/dev_ws/src
   ```

2. **Clone the Repository**: Clone this repository to your local machine using Git.
   ```bash
   cd ~/dev_ws/src
   git clone https://github.com/rakshitx1/ros_template robo
   ```

3. **Building Project**: Use colcon to build the project
   ```bash
   cd ~/dev_ws
   colcon build --symlink-install
   ```

4. **Explore the Structure**:
   - **`config/`**: Configuration files, such as YAML files.
   - **`description/`**: URDF (Unified Robot Description Format) files written in Xacro.
   - **`launch/`**: ROS launch files for starting nodes and configuring robot setups.
   - **`worlds/`**: Simulation world files.
   - **`README.md`**: This file, providing an overview of the template and instructions for use.