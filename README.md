# GSOCExampleProject
This is an example project for the [UDisplayTypes](https://github.com/robcog-iai/UDisplayTypes) repository. The plugin and all the other needed plugins are already set up in an unreal project.

### Installation 
Clone this repository with:

`git clone --recurse-submodules https://github.com/bjoernveit/GSOCExampleProject.git`

or just clone the submodules yourself.

### Usage 
After cloning everything just start up the project in Unreal. The editor Modes should have an extra UROSBridgeEd Tab now, looking like this:

![ROSBridgeMode](https://github.com/bjoernveit/GSOCExampleProject/blob/master/Documentation/RosbridgeED.PNG)

Put in the network parameters for your running [rosbridge_server](http://wiki.ros.org/rosbridge_server) and select the "VisManager" from the Callbacks -> Publisher List dropdown-menu. Now hit Connect and the UDisplayType Services will be published in the ros world.

Below is a video of a demo ros package, that can be found [here](https://github.com/bjoernveit/gsoc_example_project_demo).


[![Example video](http://img.youtube.com/vi/MVXwL6sPjy4/0.jpg)](https://youtu.be/MVXwL6sPjy4 "Example showcase")
