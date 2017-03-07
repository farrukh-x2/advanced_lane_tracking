
## Advanced Lane Finding Project

In this project, the goal is to write a software pipeline to identify in a video the lane boundaries, determine the curvature of the road and offset of the vehicle from the center

The Project
---

The goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

Usage
---
Cloning the repository and running the notebook is all that's needed to make the project work

Files
---
The images for camera calibration are stored in the folder called `camera_cal`.  The images in `test_images` are for testing the pipeline on single frames.

The examples of the output from each stage of your pipeline in the folder are saved in folder `ouput_images`. The video called `project_video.mp4` is the video the pipeline works on.  

`advanced_lane_finding` files contain the output. the mp4 is the original video and gif is displayed below:

![](advanced_lane_finding.gif)

Notebook
---
The `Jupyter_Notebook_Advanced_Lane_Finding.ipynb` notebook individually processes through each of the steps detailed above with accompanying images
