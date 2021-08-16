# Catheter-Motion-System-Thesis
Procect steps

Step 1:
1) Install arduino
2) Install arduino ros package using this link https://github.com/ros-drivers/rosserial,
3) Place StepperDriver-1.3.1 library files into the Arduino Library file
4) Run multiaxis_steppermotor_roscontroller code inside the Arduino microcontroller

Step 2:
1) Use Dynamixel Wizard program to appoint motor id as a 1
2) https://github.com/ROBOTIS-GIT/DynamixelSDK, install dynamixel_sdk package
3) https://github.com/ROBOTIS-GIT/dynamixel-workbench, install dynamixel_workbench packege
4) Easiest way to install dynamixel packages is follow this link descriptions https://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_workbench/#position-controller

Step 3:
1) https://github.com/qt/qt5, install qt5 package

Step 4:
The required python modules instillation are given below:
1) pip install opencv-python
2) pip install -U scikit-learn
3) pip install scipy

Step 5:
1) Download rar file
2) Place launch file to dynamixel launch file
3) Place yaml file to dynamixel yaml file
4) Place script file to inside the src file

Step 6:

Run the following command Project command

1) roscore

2) roslaunch dynamixel_workbench_controllers dynamixel_controllers_current2.launch

3) rosrun rosserial_python serial_node.py /dev/ttyACM0

4) rosrun dynamixel_workbench_controllers step.py

5) rosrun dynamixel_workbench_controllers smc3_5_new.py 

6) python catheter_motion_control2.py
