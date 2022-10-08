# Great project by Chris Albertson,  

very clear and understandable for non-geniuses like me, without the dependency orgies caused by ROS :-)

My project "pyro" is intended to be, very similar to "SpotMicroModular", an easy to reproduce and maintain four-legged robot.  The SpotMicroModular project is by far more developed and more professionally implemented than "pyro" and I am looking forward to rebuild "SpotMicroModular". Maybe I can incorporate some of my ideas.


It's more or less easy to reproduce:

conda create -n env385 python==3.8.5  
python 3.9 throws an error 'HTMLParser' object has no attribute 'unescape' I could not fix yet)

conda activate env385  

quad_controller:  
/home/pi/.conda/envs/env385/bin/pip install PySimpleGUI  
/home/pi/.conda/envs/env385/bin/pip install numpy  
/home/pi/.conda/envs/env385/bin/pip install matplotlib  
/home/pi/.conda/envs/env385/bin/pip install adafruit-circuitpython-servokit  
/home/pi/.conda/envs/env385/bin/pip install scipy  

python3 main.py   
-> works  

testing:  
/home/pi/.conda/envs/env385/bin/pip install PySimpleGUIWeb  
/home/pi/.conda/envs/env385/bin/pip install adafruit-circuitpython-mpu6050  
-> works  
###############################  

# Spot Micro Modular

This repository holds my version of “Spot Micro” which was originated by Thingiverse user “KDY0523”.  

### Motivation

There are many Spot Micro projects on the Internet.  They are all derived from the same KDY0523 original.  I wanted a project that could incorporate some of the best idea from other Spot Micro versions, plus some of my own ideas.  One of my main goals was to make a modifiable design.  I wanted modular and swapable parts.


The CAD files were all re-drawn, but retain the look and dimension of the original as much as possible. 

This Spot Micro uses a Raspberry Pi4 running Ubuntu Linux as the controller.  But the electronics are mounted to a tray and can be sapped out as a pre-wired unit, battery, power supplies, computer and all.

### How To Build

You can simply 3D print all the STL files and install the software on the Pi4 and you will in theory have a copy of my latest version.  Or, you can download or clone a related version from this repository and get file versions that should all work together.
