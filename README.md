### Bachelor Graduation Project: Egyptian License Plate Recognition with Arabic Letters Using C++

This project aims to develop a system for recognizing Egyptian license plates, which include Arabic letters, using C++. The project is divided into three stages:

#### 1. Detection
- **Canny Edge Detection**: Apply the Canny edge detection algorithm to identify the edges within the image.
- **Morphological Operation and Flood Fill**: Perform morphological operations and flood fill to enhance the edges and fill any gaps.

#### 2. Segmentation
- **Find Contour Algorithm**: Utilize the find contour algorithm to locate and extract the contours of the license plate from the image.

#### 3. Optical Character Recognition
- **Feature Extraction Algorithms**:
  - **PCA (Principal Component Analysis)**: Use PCA to reduce the dimensionality of the feature set while preserving important information.
  - **Hu-Moment**: Apply Hu-Moment invariants to capture shape features of the characters.

- **Classification Algorithm**:
  - **K-Nearest Neighbors (KNN)**: Implement the KNN algorithm to classify the extracted features and recognize the characters on the license plate.

These stages collectively contribute to a robust system capable of accurately detecting, segmenting, and recognizing Arabic characters on Egyptian license plates using C++.
