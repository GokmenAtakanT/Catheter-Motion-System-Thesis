# Catheter-Motion-System-Thesis
Procect step
Step 1:
1) Download rar file
2) Place launch file to dynamixel launch file
3) Place yaml file to dynamixel yaml file
4) Place script file to inside the src file

Step 2:
1) Install arduino
2) Install arduino ros packeges
3) Place StepperDriver-1.3.1 library files into the Arduino Library file
4) Run multiaxis_steppermotor_roscontroller code inside the Arduino microcontroller

Step 3:
1) Use Dynamixel Wizard program to appoint motor id as a 1


Step 4
Run the following command Project command

1) roscore

2) roslaunch dynamixel_workbench_controllers dynamixel_controllers_current2.launch

3) rosrun rosserial_python serial_node.py /dev/ttyACM0

4) rosrun dynamixel_workbench_controllers step.py

5) rosrun dynamixel_workbench_controllers smc3_5_new.py 

6) python catheter_motion_control2.py
