# 6-Axis Robotic Arm

This project is a custom-built 6-axis robotic arm that I designed and built from the ground up. 
The arm has six degrees of freedom, allowing it to move similarly to a human arm. I designed the mechanical parts myself and used a combination of 3D printing, custom gears, and off-the-shelf components. The gripper use MG996R V17 servo

A major part of the project has been figuring out the geometry of the arm. I measured each link and joint, defined the joint limits, and used those measurements to build a digital model of the arm. I am also creating a URDF model so that I can simulate the robot and eventually control it using ROS.

The control side of the project is being developed alongside the mechanical system. The plan is to use forward and inverse kinematics to calculate the position and orientation of the end effector. This should allow the arm to move to a specific point instead of manually controlling every servo.

The electronics are also being designed as part of the project. Rather than relying entirely on pre-built wiring, I am designing a custom PCB to handle the different components and power requirements of the robot.

One of the things I want to experiment with later is turning the arm into a 3D printer by replacing the gripper with a printing head. This would make the robot more than just a robotic arm and let me explore tool-changing and automated manufacturing.

This project is still a work in progress. There will probably be a lot of redesigns, broken parts, and things that don't work the first time, but that's also the point of building it myself.



<img width="670" height="792" alt="image" src="https://github.com/user-attachments/assets/6a2e9391-9f03-4887-a278-0bece15e793b" />


i designed this robotic arm in onshape and it uses planetary mechanism mainly but for the wrist ive made a 2dof wrist 



**<img width="670" height="792" alt="image" src="https://github.com/user-attachments/assets/e3788699-8cb2-4ba2-b802-362e8b7d11f0" />
**



and then ive made the claw/ gripper 


<img width="884" height="548" alt="image" src="https://github.com/user-attachments/assets/45dcea9a-363b-4ae7-8a51-0cd4f4c5a6c4" />
