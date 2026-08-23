# 6-Axis Robotic Arm

This project is a custom-built 6-axis robotic arm that I designed and built from the ground up. 
The arm has six degrees of freedom, allowing it to move similarly to a human arm. I designed the mechanical parts myself and used a combination of 3D printing, custom gears , almost each joint is a planetary mechanism since i really wanted to learn that and i learnt that in onshape .  The gripper usse MG996R V17 servo


The control side of the project is a custom pcb which is handled by a custom arduino uno nano that i made . the main pcb usees a4988 stepper motor drivers to drive each and every motor and the servo motor for the gripper i have connected directly . The plan is to use forward and inverse kinematics to move to a specific point instead of manually controlling every joint.



One of the things I want to experiment with later is turning the arm into a 3D printer by replacing the gripper with a printing head. This would make the robot more than just a robotic arm and i could then print alot of stuff from a arm that itself was 3d printed bahahahhahahaa

 There will probably be a lot of redesigns, and ill keep updating the journal.md of this repo for that 


<img width="670" height="792" alt="image" src="https://github.com/user-attachments/assets/6a2e9391-9f03-4887-a278-0bece15e793b" />


i designed this robotic arm in onshape, 

joint 1 - 5 uses planetary gear mechanism where the sun gear is attached to the nema 17 motor



**<img width="670" height="792" alt="image" src="https://github.com/user-attachments/assets/e3788699-8cb2-4ba2-b802-362e8b7d11f0" />
**



and then ive made the claw/ gripper 


<img width="884" height="548" alt="image" src="https://github.com/user-attachments/assets/45dcea9a-363b-4ae7-8a51-0cd4f4c5a6c4" />
