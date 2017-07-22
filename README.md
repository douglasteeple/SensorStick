# SensorStick
This software is part of the perception lessons in the [Udacity Robotics Nanodegree Program](https://www.udacity.com/robotics). Sensorstick performs object segmentation on 3D point cloud data using `python-pcl` based on the [Point Cloud Library](http://pointclouds.org/).  

The steps are:

1. Load a point cloud file example -- the tabletop, with objects on it.

2. Perform Voxel Grid Downsampling to reduce the image size.

3. Implement a Pass Through Filter.

4. Perform RANSAC plane segmentation.

5. Extract inliers - the table.

6. Extract outliers - the objects on the table.

7. Use the Euclidean distance to find clusters (individual objects).

8. Color the individual objects.

9. Publish the tabletop and objects as ROS messages to the Gazebo simulation.

These steps are implemented as a ROS node using the publisher/subscriber method.
