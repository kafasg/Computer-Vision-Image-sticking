# Computer-Vision-Image-sticking
## Image Feature Matching and RANSAC
This repository contains a Python script for image feature matching using methods such as Harris Corner Detection, Scale-Invariant Feature Transform (SIFT), and RANSAC for outlier removal.

## Dependencies
This script requires the following libraries:

- OpenCV (cv2)
- NumPy
- matplotlib
- sklearn

## Running the Script
Before running the script, ensure that you have all the dependencies installed. You can then run the script using Python 3 as follows:


## Functions
Here is a brief description of each function:

- Get_harris_Corners: Computes the Harris Corners of an image.
- compute_SIFT: Computes the SIFT descriptors of an image.
- norm_descriptors: Normalizes the descriptors of an image.
- euklidian_dist_descriptor: Calculates the Euclidean distance between two sets of descriptors.
- Normalized_corr: Calculates the normalized correlation between two sets of descriptors.
- matches: Finds the best matches between two images.
- find_2_line: Finds the coefficients for the Affine Matrix.
- Ransac: Implements the RANSAC algorithm to remove outliers.
- Mean_SE: Calculates the Mean Square Error of the distance between the point coordinates in one image, and the transformed coordinates of the matching points in the other image.
- assignment_1: This is the main function that takes in the file names of the two images to be compared and several other parameters, and then executes the feature matching and RANSAC processes.

## Note
The code is quite computation-intensive due to the feature matching process. It might take a long time to run for large images or a large number of features. Consider downsizing the images or reducing the number of features if the script takes too long to run.
