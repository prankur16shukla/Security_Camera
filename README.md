# Security Camera Using Python (Introduction)
In this project we have a created a python script to record the feed from the camera whenever any face or body is detected.
We have used the openCV library of python to get the feed from our webcam and used pretrained libraries by 
applying haarcascades to detect faces and bodies.
The script will record the feed when it detects any face or body in the frame, however if there is no
face of body detected it will by deafult record for 5 seconds and post that stop the recording. These recording are
being saved in the folder that can be used for different purposes.
