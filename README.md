# Midterm

# Robot Arm URDF

This repository contains a URDF (Unified Robot Description Format) model for a robot arm, along with launch files for visualization in RViz and Gazebo simulation.

## Prerequisites

Before running the launch files, ensure you have the following installed:

- ROS (Robot Operating System)
- Gazebo (for simulation)
- RViz (for visualization)

## Usage

1. Clone this repository to your ROS workspace:

    ```
    git clone https://github.com/yourusername/robot_arm_urdf.git
    ```

2. Navigate to your ROS workspace:

    ```
    cd /path/to/your/ros/workspace
    ```

3. Source the ROS setup file:

    ```
    source devel/setup.bash
    ```

4. Launch RViz to visualize the robot arm:

    ```
    roslaunch robot_arm_urdf display.launch
    ```

5. Launch Gazebo to simulate the robot arm:

    ```
    roslaunch robot_arm_urdf gazebo.launch
    ```

## Additional Notes

- This URDF model is for demonstration purposes and may not accurately represent a physical robot arm.
- Feel free to modify the URDF files to match your specific robot arm configuration.
- For troubleshooting and additional support, please create an issue in this repository.

Enjoy exploring the robot arm in RViz and Gazebo!
