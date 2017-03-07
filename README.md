
## Advanced Lane Finding Project

The goals / steps of this project is to identify lanes on a road, determine the curvature and offset of the vehicle from the center.

#### The notebook in the repository dives deep into the details for each step (along with visual outputs from each step). The steps include:


* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

## GIF of Output
![](advanced_lane_finding.gif)

### Original video (project_video.mp4) and processed video in the repository (advanced_lane_finding.mp4)

#### camera_cal contains images used to calibrate and undistort the camera


#### test_images contains images used to tune the algorithm

#### output_images contains images saved from the jupyter notebook
