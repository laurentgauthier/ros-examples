# ROS C++ example code

This repository contains a short list of example ROS packages
programmed in C++.

## Overview

### License

This code is in part copy paste from the ROS tutorials, and therefore is also
released under the MIT license.

### ROS Packages

TBD

## How to use

These instructions assume that your are using ROS Kinetic on Ubuntu 16.04.

Instructions for other platforms/releases should be rather similar.

### Create a ROS workspace

Here is an example of how to setup a ROS workspace which is a pre-requisite
for the download and build of the present code.

    $ source /opt/ros/kinetic/setup.bash
    $ mkdir -p ~/ros_workspace/src
    $ cd ~/ros_workspace
    $ catkin_make
    $ source devel/setup.bash
    $ 

### Download

The present repository should be cloned under the `src` directory created
in the ROS workspace:

    $ cd ~/ros_workspace/src
    $ git clone https://github.com/laurentgauthier/ros-examples

### Build

The `catkin_make` command searches for the ROS packages recursively under the
`src` directory:

    $ cd ~/ros_workspace
    $ catkin_make

### Run

TBD
