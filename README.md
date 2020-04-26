# Sensor_Fusion_Nanodegree_Udacity
Repo for projects and content related to Udacity 's Sensor Fusion Nanodegree

# Main concepts
----------------

1. Lidar
---------------- 
a. PCL library, RANSAC, kd tree implementation
b. Basic object classification using Lidar point clouds in
   a simulated environment

2. Camera
----------------
a. Analysing pros and cons of different image feature 
   Detectors, Descriptors and matching algorithms such 
   as SIFT, FAST, ORB, BRIEF, FLASK, BRUTE FORCE etc
b. Fusing object detection data (using std YOLOv3 DL
   model) and Lidar point cloud data to localise 
   adjacent vehicles and estimating TTC. 
   Data source: KITTI dataset 

3. Radar
----------------
a. FMCW radar working principle basics
b. Use of FFT for processing Radar data


4. Kalman Filters
----------------
a. Use of Kalman filters (LKF, EKF, UKF) for state estimation 
b. Prediction of trajectory of vehicles fusing Lidar, Radar and
   Ego vehicle state using UKF setup in a simulated environment
