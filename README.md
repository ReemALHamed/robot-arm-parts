# robot-arm-parts
In this project we want to simulate the process of building the robot arm, we connect the parts togather using Cinema 4D.

## 1. Get The Arm Parts
Go to (https://github.com/smart-methods/arduino_robot_arm) and download the project , you will find the required files under the psth (arduino_robot_arm/robot_arm_pkg/meshes/stl)

![image](https://user-images.githubusercontent.com/85634099/126074606-b67cd3f3-88fc-4019-8e14-eca6f6369725.png)


## 2. Download Cinema 4D
Visit the following link (https://www.maxon.net/en/downloads/cinema-4d-r23-downloads) where you can download the program by clicking on (ONLINE AUTO INSTALLER):

![image](https://user-images.githubusercontent.com/85634099/126074599-8f3f481d-e7a6-4400-b1d7-40136547c666.png)

## 3. Gather The Parts
Now start by stacking the arm parts in the correct order, starting with the base and ending with the gripper as following:

#### A) Starting with Cinema 4D
Once you open the program you will start with a plain environment, and to add the arm parts go to File >> Open Project >> choose the arm part you want to add (ex: Base)

![image](https://user-images.githubusercontent.com/85634099/126075073-cca61e4a-e888-4df6-a98f-7d0bde731997.png)
![image](https://user-images.githubusercontent.com/85634099/126075082-05b49c27-9869-40a4-b9bf-687a17852c06.png)
![image](https://user-images.githubusercontent.com/85634099/126075096-8e8c1c63-089e-486a-ae06-3707a3795831.png)


#### B) Connecting THe Parts
To connect one part with another go to File >> Merge Project >> choose the arm part you want to add , (ex: connecting Base with Waist)
![image](https://user-images.githubusercontent.com/85634099/126075159-0902bc6c-9723-4e20-9224-ddd019665cee.png)


#### C) Add The Remaining parts
Same way , add the remaining parts and adjust them using Scale and x,y,z coordinates, and to form the robot arm correctly follow this order:
1)	Base
2)	Waist
3)	Arm 1
4)	Arm 2
5)	Gripper

![image](https://user-images.githubusercontent.com/85634099/126075342-2499a39a-9afd-480e-95c8-fc79f6c18b86.png)


## The Results !!
Follwing the previous steps resulted in constructing the arm correctly as follows:

![image](https://user-images.githubusercontent.com/85634099/126075605-2f89f36c-77df-4ab8-be0e-12eb9f9f7b7e.png)

And to save the arm as an STL file go to File >> Export >> STL

![image](https://user-images.githubusercontent.com/85634099/126075583-49b4a733-20e2-4224-bd93-8dfd6b6a51d3.png)

