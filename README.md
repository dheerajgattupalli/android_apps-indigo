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
 2) Import into Android Studio.Build using gradle 2.2.1
