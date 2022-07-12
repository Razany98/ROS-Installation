# ROS 
is an open-source meta robotics operating system. 
With it you can easily simulate your robot before developing it in the real world. 

##### For downloading ROS (Robot Operating System) on your operating system you will go through 3 steps. 

### 1 - Download the Oracle Virtualbox: 
You are going to use a virtual host to download Ubuntu and ROS and their packages, so you need Virtualbox; you can download it from this link: https://www.virtualbox.org/wiki/Downloads 

This is the VirtualBox homepage when the installation is done: 

![](images/VM.png)

### 2 - Download Ubuntu on VirtualBox: 
After installing many versions of Ubuntu, the best version that worked & installed successfully with me is Ubuntu 20.04. So, I recommend downloading this version. For the installation instructions follow the steps in the below video. 
https://www.youtube.com/watch?v=x5MhydijWmc&t=973s 

📌 Put in mind that inatalling ROS and Ubuntu may take long time upto 2 hours. 

When this process is done, you will see that you can't maximize the window & Can't copy/paste. 
To fix this problem you will need to download the GuestAddition, to do that, follow the following steps: 
- From the upper toolbox on the Ubuntu window choose Devices then Insert Guest Additions CD image... 

![](images/GuestAddition.png) 

- Choose Run GuestAddition 

![](images/Run-Guest-Additions.png)

- Wait until the installation is done; log out or close the window and you will see that the GuestAddition is added. 

![](images/Guest.png)

### 3 - Download ROS and Gazebo: 
You may follow the steps in this article: https://varhowto.com/install-ros-noetic-ubuntu-20-04/ 
For step 4 I recommend to install the ros-noetic-desktop-full package in case you want to install gazebo. 
Gazebo is a userinterface software simulator including libraries and cloud services. 
