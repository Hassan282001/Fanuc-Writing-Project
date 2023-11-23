# Fanuc-Writing-Project
## Introduction
This project is part of my ENGG4460 (Robotic Systems) lab and covers the control of a Fanuc CR-4iA Collaborative Robotic Arm. The objective was to Program the Robot Arm to autonomously write an arbitrary three-letter word, consisting of alphabetic characters 'S', 'L', 'O', 'W', 'U', 'B'. This project is to be used in applications like 3D printing and automated writing.

## File Descriptions
**main.ipynb:** Jupyter notebook with the complete implementation of the robotic arm's control logic, including AI-driven decision-making for writing.  

**fanuc_pcdk_client.py:** Handles communication with the Fanuc robotic arm, including sending commands and processing responses.  

**robot_loc_joint.py:** Manages joint coordinates of the robot, essential for the precise articulation of the arm.  

**robot_loc_world.py:** Handles world coordinates of the robot, crucial for positioning the robot arm in 3D space.  

**LICENSE:** Apache License, Version 2.0.  


## Dependencies
- Python 3.x.  

- Fanuc CR-4iA Collaborative Robotic Arm, properly set up and enabled for programming.  

- Required Python libraries (listed in requirements.txt).  


## Constraints
- The robotic arm must be a Fanuc CR-4iA model, correctly configured and enabled.  

- The system is designed to write words consisting of the characters 'S', 'L', 'O', 'W', 'U', 'B' only.    

