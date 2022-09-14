# human-pose-quaternion-extraction
A research project repository containing algorithms to extract human pose quaternions using 2D cameras 

# Quaternion based Orientation Extraction from a Human Skeletal Pose Estimate using 2-D Cameras

In this paper, we present a novel implementation of an algorithm to extract a quaternion from a two dimensional camera frame for estimating a contained human skeletal pose. The problem of pose estimation is usually tackled through the usage of stereo cameras for obtaining depth and euclidean distance for measurement of points in 3D space. However, this task comes with a high computational cost with a relatively high detection latency as well, requiring the use of expensive hardware components. By making use of MediaPipe, a framework for building perception pipelines for human pose estimation, the proposed algorithm extracts a quaternion from a 2-D frame capturing an image of a human object at a sub-fifty millisecond latency while also being capable of deployment at edges with a single camera frame and a generally low computational resource availability.
