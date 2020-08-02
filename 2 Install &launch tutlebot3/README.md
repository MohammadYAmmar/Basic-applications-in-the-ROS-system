Initially I tried to be like the first step through Ubuntu 20 on the ROS version noetic-ninjemys but tried many methods and steps and did not work stable on the fake system

The solution was to use an online simulation website, which is:
#### <p align="center"> [ROS Development Studio](https://rds.theconstructsim.com/)
</p>

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/setup%20theconstructsim%201.png) 

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/setup%20theconstructsim%202.png) 

Then I created an account and then set specifications for the free package, and ROS comes with it.

And I started running turtlebot simulation

Write or copy to paste in terminal:
`cd ~/catkin_ws/src/`

`git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git`

`cd ~/catkin_ws && catkin_make`

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/step%201.png) 

then write this to lunching turtlebot

`export TURTLEBOT3_MODEL=burger`

`roslaunch turtlebot3_fake turtlebot3_fake.launch`

The result will appear, some errors may occur

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/step%202.png) 

Results I have noticed direct features in the simulation site of this thing with different worlds and pieces of control

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/result%201.png) 

Such a ball is a product found on the market like years and amusing and found ready to use

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/result%202.png) 

The free version is somewhat limited, so when you click on some of the operations, it appears the following, but it is a more beautiful and faster way of dealing and I think it does not sing for your system to be

![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/2%20Install%20%26launch%20tutlebot3/Warning%20usage.png) 

A good explanation for installing and running the copy in files here from a colleague with us in training
#### <p align="center"> [install turtulebot 3](https://github.com/ios96i/SmartMethods-internship-AI-in-robotics-3/tree/master/3.2%20install%20turtulebot%203)
</p>
