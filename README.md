# 6-Axis Robotic Arm

This project is a custom-built 6-axis robotic arm that I designed and built from the ground up. 
The arm has six degrees of freedom thus the 6DOF , I designed the mechanical parts myself and used a combination of 3D printing, custom gears ,and  almost each joint is a planetary mechanism since i really wanted to learn that and i learnt that in onshape .  The gripper usse MG996R V17 servo


The control side of the project is a custom pcb which is handled by a custom arduino uno nano that i made . the main pcb usees a4988 stepper motor drivers to drive each and every motor and the servo motor for the gripper i have connected directly . The plan is to use forward and inverse kinematics to move to a specific point instead of manually controlling every joint.



One of the things I want to experiment with later is turning the arm into a 3D printer by replacing the gripper with a printing head. This would make the robot more than just a robotic arm and i could then print alot of stuff from a arm that itself was 3d printed bahahahhahahaa

 There will probably be a lot of redesigns, and ill keep updating the journal.md of this repo for that 


<img width="670" height="792" alt="image" src="https://github.com/user-attachments/assets/6a2e9391-9f03-4887-a278-0bece15e793b" />


i designed this robotic arm in onshape, 

joint 1 - 5 uses planetary gear mechanism where the sun gear is attached to the nema 17 motor



<img width="670" height="792" alt="image" src="https://github.com/user-attachments/assets/e3788699-8cb2-4ba2-b802-362e8b7d11f0" />




and then ive made the claw/ gripper 
which uses a servo motor attached to a spur gear which move yet 2 another spur gears

<img width="884" height="548" alt="image" src="https://github.com/user-attachments/assets/45dcea9a-363b-4ae7-8a51-0cd4f4c5a6c4" />



# how to assemble 

print the given step files , modify them if you want to 

and then look at the assembled version and piece everything together. i will be documenting my proccess aswell when i print the parts. 

# how to assemble electronic part of project

when you get the main pcb and then the microcontroller pcb
you take the stencil and then use that stencil to apply solder paste. 
and then you remove the stencil and place each component by looking at the nicely labelled pcb 

<img width="948" height="460" alt="image" src="https://github.com/user-attachments/assets/f02fa1be-1578-4017-aa76-ec6c18e90adf" />

and then by using a hot air gun or a hotplate , reflow the solder 


# hot to assemble the main board pcb 

you take the pcb and using a soldering iron just solder the required amount of female or male pinheaders ( 2.57mm exactly) 



here is a mockup i nade using onshape of how the main pcb should look like after you assemlbe it 

