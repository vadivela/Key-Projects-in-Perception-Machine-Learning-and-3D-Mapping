
# Key Projects in Perception, Machine Learning, and 3D Mapping

This repository includes core perception and mapping projects focused on 3D point cloud processing, object tracking, machine learning, and augmented reality. The work demonstrates end-to-end development from algorithm design to implementation, testing, and visualization.

## Projects

### 1. 3D Point Cloud Processing
Developed custom algorithms for **RANSAC Plane Fitting** to robustly estimate planar surfaces in noisy 3D point clouds, and implemented **Iterative Closest Point (ICP)** from scratch to align separate point clouds. These methods enabled accurate plane fitting and precise point cloud registration for both synthetic and real-world data.

### 2. Deep Learning for Dimensionality Reduction and Classification
Built and trained an **autoencoder** on the Fashion-MNIST dataset to extract compressed latent representations. Using these features, trained a supervised classifier achieving **85% test accuracy**, highlighting strong feature extraction and generalization from low-dimensional spaces.

### 3. Augmented Reality with ArUco Tags
Developed a real-time **AR system using OpenCV and ArUco markers**. Estimated 3D poses and projected virtual cubes onto the detected markers using camera calibration data. Visual results confirmed accurate rendering and pose alignment from multiple viewpoints.

### 4. Dynamic Object Tracking
Implemented real-time **object tracking** across video frames using **YOLOv8** for detection and a custom tracker for maintaining unique IDs. Combined **IoU and motion estimation** to enable consistent identity tracking through occlusion and dynamic changes in the scene.

## Tools and Libraries
- Python, OpenCV, Open3D, PyTorch, Matplotlib
- YOLOv8 (Ultralytics), t-SNE (scikit-learn)
- ArUco module (OpenCV), KD-Tree, SVD
- ROS2, Gazebo (for simulation-related work)

