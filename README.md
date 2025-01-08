
# Computer Vision Coursework

This repository contains the coursework project for the **Computer Vision** module at **Imperial College London**. The project explores key techniques in computer vision, including feature extraction, feature matching, and 3D surface reconstruction.

## Overview

The notebook implements:
1. **Salient Feature Detection**: Using SIFT to detect and describe features in video frames.
2. **Feature Matching**: Finding correspondences between frames using descriptor matching.
3. **Epipolar Geometry**: Estimating the fundamental matrix and applying the epipolar constraint.
4. **3D Surface Reconstruction**: Estimating disparities and reconstructing the scene in 3D.

## Features

- **Image Processing**: Includes grayscale conversion, feature detection, and visualization of keypoints.
- **Visualization**: Saves and displays results such as detected keypoints and matched features.
- **Mathematical Computation**: Computes the fundamental matrix and compares different estimation methods.
- **Surface Area Estimation**: Uses disparity maps and 3D reconstruction to calculate geometric properties like the area of a swimming pool.

## Getting Started

### Prerequisites

- Python 3.8+
- Required libraries:
  ```bash
  pip install numpy opencv-python matplotlib
  ```

### Usage

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Run the Jupyter Notebook to execute the code and view results:
   ```bash
   jupyter notebook Computer_Vision_Coursework.ipynb
   ```

## Results

The project includes the following outputs:
- Keypoint visualization.
- Matching features across frames.
- Fundamental matrix computation.
- Disparity maps and 3D reconstruction.

## License

This project is for academic purposes and follows the coursework submission guidelines of Imperial College London. Please do not directly reuse the code for academic submissions without proper attribution.
