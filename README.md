# EX:05
# VImage-Smoothing-and-Sharpening-Using-OpenCV

# AIM

To implement image smoothing and sharpening filters using OpenCV for enhancing image quality, reducing noise, and improving edge details.

# SOFTWARE REQUIRED

Python 3.7 (Anaconda)
Jupyter Notebook (for interactive development and execution)

# EXPLANATION

Image filtering is a fundamental image processing technique used to improve image quality and extract useful information. Smoothing filters help reduce noise and unwanted variations in images, while sharpening filters enhance edges and fine details. OpenCV provides various filtering techniques such as Averaging, Weighted Averaging, Gaussian Blur, Median Blur, and Laplacian filtering to perform these operations effectively.

# ALGORITHM

Step 1: Import the required libraries such as OpenCV, NumPy, and Matplotlib.

Step 2: Read the input image using cv2.imread().

Step 3: Convert the image from BGR format to RGB format for proper visualization.

Step 4: Apply the Averaging filter to smooth the image by replacing each pixel value with the average of its neighboring pixels.

Step 5: Apply the Weighted Averaging filter to smooth the image while giving higher importance to specific neighboring pixels.

Step 6: Apply the Gaussian filter to reduce image noise using a Gaussian kernel.

Step 7: Apply the Median filter to remove impulse noise while preserving edges.

Step 8: Apply the Laplacian sharpening filter to enhance edges and fine image details.

Step 9: Apply the Laplacian operator for edge detection.

Step 10: Display the original image and all filtered output images for comparison.

# RESULT

Thus, image smoothing and sharpening filters were successfully implemented using OpenCV in Python. The smoothing filters reduced noise and improved image quality, while the sharpening and edge detection filters enhanced image details and boundaries effectively.
