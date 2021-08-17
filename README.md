# left_cam_acq
    <arg name="arg1"/>
    <node pkg="mur_left_image_acq" type="mur_left_image_acq" name="mur_left_image_acq" args="$(arg arg1)" output="screen"/>

roslaunch my_launch.launch arg1:="1 1" 

where each "1" stands for lightSetting, exposureTimeSetting

lightSetting 
1 - off
2 - daylight 5000K
3 - daylight 6500K

exposureTimeSetting 
1 - defaultExposureTime == 5000us
2 - 4000us
3 - 3000us
4 - 2000us
5 - 1000us
6 - 500us
7 - 250us
8 - 125us
9 - 100us
10 - 75us
11 - 50us
12 - 25us

frameRateSetting
1 - 160
2 - 5
3 - 10
4 - 15
5 - 20
6 - 25
7 - 30
8 - 35
9 - 40 
10 - 45
11 - 50 