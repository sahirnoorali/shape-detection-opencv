# Detecting Shapes from Noisy Image Using OpenCV

This project utilizes OpenCV functions to smoothen the noise in the image and extract shapes

## Code
The code does the following in sequence:

- Reading the image and converting from RGB to Gray scale
- Removing Gaussian Noise via Gaussian Blur
- Applying Inverse Binary Adaptive Thresholding
- Finding all Countours in the processed image
- Filtering countours based on their area
- Initializing a new image and drawing the filtered contours 
