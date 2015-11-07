# android_apps-indigo

This is an extension to the first version of the Ros Android Sensors Driver.
    Replaced the Location Manager which uses only Gps with the Fused Location Api to increase accuracy.
The topic names are:

 /android/imu
 
 /android/fix (GPS)

Compiling:

To compile it on you machine, please follow the detailed instructions at:

Rosjava:
http://wiki.ros.org/rosjava/Tutorials/indigo/Installation

Once your environment is set, do the following steps:
 1) git clone the repo in the android_apps_indigo folder.
 2) Import into Android Studio.Built using gradle 2.2.1
 
 Using the app:
1. The Pc and Phone must be on same connection.On the pc change to ROS_MASTER_URI to http://ipaddress:11311 and run roscore
2. After opening the app it asks for the ROS_MASTER_URI. After connecting the data is published to the topics

The data is published for every 2-5 seconds till gps lock is obtained and after gps lock frequency is 1 hz.
