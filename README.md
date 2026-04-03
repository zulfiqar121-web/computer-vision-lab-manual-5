Road Lane Detection using Sobel Edge Detection

This project demonstrates a simple computer vision technique to detect edges in road or lane images using the Sobel operator. The implementation is done in Python and is designed to run in Google Colab, making it easy to test with custom images.

Overview

Edge detection is an important step in many computer vision tasks, especially in applications like autonomous driving and lane detection. In this project, the Sobel operator is used to highlight edges by calculating gradients in both horizontal and vertical directions.

The notebook allows users to upload an image and visualize both the original grayscale image and the detected edges.

Features
Upload custom road or lane images directly in Colab
Convert images to grayscale for processing
Apply Sobel operator in both x and y directions
Compute edge magnitude for better visualization
Display results side by side using matplotlib
Technologies Used
Python
OpenCV
NumPy
Matplotlib
Google Colab
How It Works
The user uploads an image using the Colab file upload feature.
The image is converted into grayscale.
Sobel filters are applied in both x and y directions to detect intensity changes.
Gradient magnitude is calculated to combine both directions.
The result is normalized and displayed as an edge-detected image.
Installation

Run the following command in your environment:

pip install opencv-python-headless
Usage
Open the notebook in Google Colab
Run all cells
Upload a road or lane image when prompted
View the original and edge-detected output
Output

The output consists of two images:

Original grayscale image
Edge-detected image using Sobel operator
Notes
The notebook contains repeated code blocks, which can be optimized into a single reusable function for cleaner implementation.
Works best with clear road or lane images with good contrast.
Future Improvements
Implement Canny edge detection for better accuracy
Add lane line detection using Hough Transform
Optimize code structure and remove redundancy
Extend to real-time video processing
Author

This project is created as part of a Computer Vision lab assignment to understand the fundamentals of edge detection techniques.
