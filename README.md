# README

## robotics.github.io
This is a collaborative project done by Nishanth Sarvanamurali, Sarvesh Kannan, Sruthi Rengarajan and Praatosh B as a part of our subject "Introduction to AI Robotics" under the guidance of Mr.Navaneeth Haridasan. 

Project Overview:
This project involves creating a detailed robotic model using MATLAB and exporting it to a URDF file for use in other robotics software. The robot model includes several components such as a base, arms, links, and a gripper, all connected through various types of joints. The model also incorporates collision properties for accurate simulation.

Key Takeaways
Rigid Body Creation: The robot is constructed from multiple rigid bodies representing different parts of the robot, such as the base, arms, links, and gripper.

Collision Properties: Each rigid body is assigned collision properties to define its physical dimensions and enable realistic simulation of interactions.

Joint Types: The project uses various joint types to connect the rigid bodies:

Fixed Joints: Used for parts that do not move relative to each other.
Prismatic Joints: Allow linear motion along a specified axis.
Revolute Joints: Enable rotational motion around a specified axis.
Visualization: The assembled robot is visualized with its collision properties to ensure that all the parts are correctly positioned and connected.

URDF Export: The complete robot model is exported to a URDF file, making it compatible with other robotic simulation environments like ROS (Robot Operating System).

Important Points
Model Accuracy: Ensure that the dimensions and positions of the collision objects are accurate to reflect the real-world scenario.

Joint Configuration: Properly configure the joint types and their respective axes to achieve the desired movements and functionalities of the robot.

Visualization: Use visualization tools to debug and verify the robot model before exporting it to URDF.

URDF Compatibility: The exported URDF file should be checked for compatibility with other robotics software to ensure seamless integration.

Usage
Model Assembly: The robot model is assembled in MATLAB using the rigid body tree class, with each part defined as a rigid body.
Collision Definition: Collision objects are added to each rigid body to define their physical space.
Joint Configuration: Different types of joints are used to connect the rigid bodies and define their movements.
Visualization: The robot model is visualized to verify the assembly and positioning of all parts.
URDF Export: The complete robot model is exported to a URDF file for use in other robotics applications.

Conclusion
This project provides a comprehensive approach to creating and simulating a robotic model in MATLAB. By defining rigid bodies, collision properties, and joints, and by exporting the model to URDF, it ensures that the robot can be accurately represented and used in various robotic simulation environments.
