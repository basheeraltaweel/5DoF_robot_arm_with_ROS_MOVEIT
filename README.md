# 5DoF Robot Arm with ROS MoveIt using SolidWorks

This GitHub repository, **5DoF_robot_arm_with_ROS_MOVEIT**, showcases the design and implementation of a 5 Degrees of Freedom (5DoF) robot arm using SolidWorks. The project includes the conversion of the mechanism to URDF format and integration with ROS MoveIt for motion planning.

## Repository Structure:

### 1. `serial_robot_5axis`

- **URDF Folder:** Contains a file named *midterm.urdf* that encapsulates all materials required for visualization in RViz and simulation in Gazebo.
- **Launch Folder:** Contains two files - *midterm_rviz* for running RViz and *midterm_gazebo* for running Gazebo.
- **YAML Folder:** Includes a file named *controllers.yaml* responsible for joint control.

### 2. `prrrrr_moveit_config`

- This folder is dedicated to motion planning with MoveIt, providing a comprehensive configuration for planning and executing trajectories.

### 3. `solid_parts`

- Houses the SolidWorks parts used in designing the robot arm.

### 4. `Capture.JPG`

- A snapshot of the robot arm design.

### 5. `demonstration.mp4`

- A video demonstration showcasing the robot arm in action.

### 6. `steps_to_follow_file_launching.pdf`

- Detailed instructions on running the code and launching the robot manipulator in ROS with RViz, Gazebo, and MoveIt.

## How to Run:

1. Clone the repository.
2. Navigate to the **serial_robot_5axis** folder.
3. Execute the launch files: *midterm_rviz* for RViz and *midterm_gazebo* for Gazebo.
4. Explore motion planning using MoveIt through the **prrrrr_moveit_config** folder.
5. Refer to *steps_to_follow_file_launching.pdf* for a comprehensive guide.

Enjoy exploring and experimenting with the 5DoF robot arm in a ROS environment!
