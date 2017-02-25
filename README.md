Turtlebot Navigation Tutorial
================================
[![Build Status](https://travis-ci.org/banuprathap/turtlebot_nav_tutorial.svg?branch=master)](https://travis-ci.org/banuprathap/turtlebot_nav_tutorial)

[![Coverage Status](https://coveralls.io/repos/github/banuprathap/turtlebot_nav_tutorial/badge.svg?branch=master)](https://coveralls.io/github/banuprathap/turtlebot_nav_tutorial?branch=master)



This is a simple navigation demo for a Turtlebot

 AUTHOR : BANUPRATHAP ANANDAN
 AFFILIATION : UNIVERSITY OF MARYLAND, MARYLAND ROBOTICS CENTER
 EMAIL : BPRATHAP@UMD.EDU

License
============
Copyright belongs to the author of this repository

MIT License

Copyright (c) [2017] [Banuprathap Anandan]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Dependencies
================================
This package depends on the following ROS packages
	1. turtlebot_navigation
	2. turtlebot_bringup
	3. move_base_msgs
	4. std_msgs

Installation
================================	
```bash
cd ~/catkin/src
git clone https://github.com/banuprathap/turtlebot_nav_tutorial.git
cd ..
catkin_make
roslaunch turtlebot_nav_tutorial navigate.launch
```
