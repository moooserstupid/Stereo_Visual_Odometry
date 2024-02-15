# Stereo Visual Odometry

This project aims to achieve odometry (finding the 6D pose of the host with respect to world space) using a system consisting of multiple cameras.
This is accomplished by using the 7/5 point algorithm to calculate the fundamental/essential matrix, then using these matrices, the cameras'
intrinsic parameters, and the differences between the data captured of the same scene by multiple image sensors simultaneously, to accomplish 
relative camera pose estimation and host triangulation. 

This technique has potential to be used in a vast array of different contexts from AR, to robotics, to SFM (Structure From Motion), to mapping and
much, much more.

Currently the program only contains a Visual Studio solution and thus can only be built and run using Visual Studio 2019+. However, I plan on adding
a cmake configuration and more descriptions about how the program works and visuals of it in action in a few days.
