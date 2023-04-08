# 3D Object Tracking



<img src="images/code_structure.png"/>
<img src="images/3d_object_viewer.png"/>
<img src="images/final_sensor_ttc.png"/>

In this project, there four major tasks: 
1. First, matching 3D objects over time by using keypoint correspondences. 
2. Second, Computing time to collision (TTC) based on Lidar measurements. 
3. Computing TTC based the camera, which requires to first associate keypoint matches to regions of interest and then to compute the TTC based on those matches. 
4. And lastly, conducting various tests with the framework. Goal is to identify the most suitable detector/descriptor combination for TTC estimation based measurements by the camera or Lidar sensor. 


## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level project directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. download yolo.weights file in dat/yolo/
5. Run it: `./3D_object_tracking`.
