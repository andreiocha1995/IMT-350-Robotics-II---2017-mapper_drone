# IMT-350-Robotics-II---2017-mapper_drone
Universidad Catolica Boliviana de "San Pablo"
# Instructor: Ing.Pinaya Gutierrez Benjamin
# Developer Rocha Eduardo Andrei

This is a project of a drone capable of mapping its environment, using sensors Kinetic for making the cloud_point, and a camera.
first, we desing a structure with SolidWroks for the body of the drone, solid exported the file to URDf file; so that way we to work with
that file in ROS.
After that, we use moveit:by setting a vvirtual floating joint between the base link of the quadrotor and teh fixed odometry link.
Make sure to comunicate correctly the moveit package to the launch from hector_quadrotor_gazebo.
Original project from AlessioT (https://bitbucket.org/AlessioT/autonomous-flight-ros.git)

We needed to install Moveit!, Hector_quadrotor package, and gazebo. I use Ros indigo for ubuntu 14.04
Video demonstration :https://www.youtube.com/watch?v=n_EQpaeoQSU&t=19s

To run the program use de command: Roslaunch prueba2 start.launch
then run the pyhton program that is inside prueba2: python tx_keyboard_ctrl.py

#testing sensors
![ima1](https://user-images.githubusercontent.com/30817507/34090197-9820db9a-e38b-11e7-8b9d-7838da50c978.png)

#Gazebo World
![image2](https://user-images.githubusercontent.com/30817507/34090241-e6c2955e-e38b-11e7-9bfa-78fd15ab12e8.png)

#RVIZ World
![image3](https://user-images.githubusercontent.com/30817507/34090251-f1f4d68a-e38b-11e7-9a66-a907c93fca9c.png)
