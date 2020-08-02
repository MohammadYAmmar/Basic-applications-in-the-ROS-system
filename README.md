# Basic-applications-in-the-ROS-system
Basic applications in the ROS system , during training at the Smart Methods Company


# 1 : Create 2 nodes publisher and Subscriber
One of the tasks of artificial intelligence in training a smart company is to get to know the Robot Operating System (ROS) 

To install the system in its latest version, I wrote a guide for this in Arabic and English
 #### <p align="center"> [How to install a ROS AR EN](https://github.com/MohammadYAmmar/How-to-install-a-ROS-AR-EN)
</p>

Here we will learn the first steps how to create  2 nodes publisher and Subscriber

# First we go to terminal in the Ubuntu system, to create publisher node
and write or copy to paste in terminal:

 `$ roscd basic_tutorial`
 
If not implemented, try the following

`$ sudo apt install python3-rosinstall`



Then we create a folder to put files on
 ```
$ mkdir scripts
$ cd scripts
 ```

 to get the file with the name talker, which is in Python format
  ```
$ wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/talker.py
$ chmod +x talker.py
 ```
![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/1%20Create%202%20nodes%20%20publisher%20and%20Subscriber/step%201.png) 


It will download the file to the folder and have attached it 
You can be seen through the following command
 `$ more talker.py`
 
![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/1%20Create%202%20nodes%20%20publisher%20and%20Subscriber/ls%20more%20talker.png) 

# create Subscriber node
  ```
$ roscd beginner_tutorials/scripts/
$ wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/listener.py
$ chmod +x listener.py
  ```
 ![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/1%20Create%202%20nodes%20%20publisher%20and%20Subscriber/step%202.png) 

It will download the file to the folder and have attached it 
You can be seen through the following command
 `$ more listener.py`
 ![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/1%20Create%202%20nodes%20%20publisher%20and%20Subscriber/ls%20more%20talker.png) 
 
 Here is the folder after setting up nodes
 
 ![much-a image](https://github.com/MohammadYAmmar/Basic-applications-in-the-ROS-system/blob/master/1%20Create%202%20nodes%20%20publisher%20and%20Subscriber/files%20after%20process.png) 

---
#  Install &launch tutlebot3
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
