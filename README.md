# Wall-F


**##Camera**

##For usb camera

#step 1
#insall guvciew software
#run 'sudo apt-get install guvcview' on linux terminal.
#step 2
#connect our usb camera to Pi, then go to /dev directory, run 'ls'.
#check if there is a 'video0' device, if yes, connected successfully.
#use terminal to run guvcview: 'sudo guvcview'
#if there are any problem, check resolution/frame rate setting on GUVCViewer controls/Video & Files
#step 3
#once the camera works proporly on expect resolution, we can instal OpenCV

##For Pi camera board

#step 1
#connect Pi camera board to Pi, ref:  http://www.raspberypi.org/help/camera-module-setup/
#step 2
#run config tool: 'sudo raspi-config'
#step 3
#select 'Enable Camera' to enable, then, reboot Pi.
#(instruction for taking photo and name as 'image': raspistill-o image.jpg)
#step 4
#install picamera python library to access camera on python: 
#'sudo apt-get install python-picamera python3-picamera python-rpi.gpio'
#step 5
#install OpenCV

##OpenCV installation steps
#1.sudo apt-get update (to upgrade system to lateset version
#2.sudo apt-get install build-esential
#3.sudo apt-get install libavformat-dev (provide encodeing and decoding function for audio/video stream
#4.sudo apt-get install fmpeg (provide transcoding function for audio/video stream
#5.sudo apt-get install libcv4.6 libcvaux4.6 libhighgui4.6
#6.sudo apt-get install python-opencv
#7.sudo apt-get install opencv-doc
#8.sudo apt-get install libcv-dev
#9.sudo apt-get install libcvaux-dev
#10.sudo apt-get install libhighgui-dev
#11.sudo apt-get install python-numpy





