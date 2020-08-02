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
