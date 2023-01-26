# Stereo-Vision-GUI
This Graphical User interface (GUI) was developed to facilitate the the process of capturing imagery and video data for a technology demonstration of an Electro-Optical Stereo Vision Aircraft Approach Tracker system. System used machine vision technology to identify aircraft on landing-approach and track position/accuracy relative to ideal glideslope.

The GUI links to functions that automates the process of calibrating the FLIR camera system by feeding it a series of calabration images from which the intrinsic and extrinsic paramters of the stereo-camera system can be detemined.

Using these extracted parameters each frame of the aircraft approach video data is rectified to allow for the application of stereo-vision to determine the depth/distance (x, y, z) of the approaching aircraft.

The GUI was also used to trigger the camera system to capture pictures or initiate video recording.

open source PyQT5 was the chosen python library used to create the GUI

open source OpenCV was the chosen python library used for image and video processing

