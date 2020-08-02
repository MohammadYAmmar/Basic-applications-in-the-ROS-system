# 1 Create 2 nodes publisher and Subscriber
One of the tasks of artificial intelligence in training a smart company is to get to know the Robot Operating System (ROS) 

Here we will learn the first steps how to create  2 nodes publisher and Subscriber

First we go to terminal in the Ubuntu system, to create publisher node
and write or copy to paste in terminal:
 `$ roscd basic_tutorial`
If not implemented, try the following
`sudo apt install python3-rosinstall`

Then we create a folder to put files on
 ```
$ mkdir scripts
$ cd scripts
 ```
 
 to get the first file with the name talker, which is in Python format
  ```
$ wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/talker.py
$ chmod +x talker.py
 ```
It will download the file to the folder and have attached it 
You can be seen through the following command
 `$ more talker.py`


https://github.com/MohammadYAmmar/How-to-install-a-ROS-AR-EN
