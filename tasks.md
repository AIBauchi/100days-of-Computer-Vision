# 100 Days of Computer Vision - Tasks

### Days 1-6: Working with OpenCV in a Local Environment

#### Day 1: Camera Image Capture
- Load an image from the camera and save it to the local directory.

#### Day 2: Image Loading and Resizing
- Load an image from a file and resize it to a specific dimension.

#### Day 3: Loading and Grayscale Conversion
- Load an image from the URL [https://aibauchi.com.ng/logo.png](https://aibauchi.com.ng/logo.png) and convert it to grayscale.

#### Day 4: Image Background Removal
- Load the grayscale image from Day 3 and remove the image background.

#### Day 5: Drawing Circle on Live Camera Feed
- Draw a circle on the live camera feed in real-time.

#### Day 6: Real-time Annotation on CV Camera Frame
- Annotate your username and the date on the lower-left corner of the CV camera frame and display it in real-time.

### Days 7-17: Advanced OpenCV Operations on Images

#### Day 7: Blob Analysis by Convexity
- Perform Blob analysis using the convexity feature on an image from 'images/day6.jpg'.

#### Day 8: Canny Edge Detection on Live Video Feed
- Apply Canny edge detection to the live video feed from the camera.

#### Day 9: OpenCV Averaging
- Perform image smoothing using OpenCV averaging.

#### Day 10: OpenCV Median Blur
- Implement the median blur operation using OpenCV.

#### Day 11: OpenCV Gaussian Blur
- Apply Gaussian blur to an image using OpenCV.

#### Day 12: OpenCV Bilateral Filter
- Implement a bilateral filter on an image using OpenCV.

#### Day 13: Adaptive Thresholding for Pencil Sketch
- Utilize adaptive thresholding to create a pencil sketch effect on the live camera feed.

#### Day 14: Contours and Shape Detection
- Implement contour detection and shape identification on any image. Refer to OpenCV documentation for implementation details.
- Detect basic shapes like circles, rectangles, and triangles using contour properties and annotate them

#### Day 15: Mouse Event as a Paint Brush
- Create a program that allows the mouse to be used as a paintbrush on a frame from the camera feed. Refer to OpenCV documentation for implementation details.

#### Day 16: Live Face Detection
- Implement live face detection using OpenCV.
- Refer to [YouTube - OpenCV Face Detection tutorial](https://www.youtube.com/watch?v=5cg_yggtkso) for guidance.

#### Day 17: Facial Recognition Implementation
- Implement facial recognition using only the `opencv` and `face_recognition` Python libraries.
- Refer to [ MyGreatLearning - Face Recognition tutorial](https://www.mygreatlearning.com/blog/face-recognition/) for guidance.

### Days 18-20: Deep Learning Model Building and Hyperparameter Tuning

#### Day 18: Handwritten Digit Recognition with Keras
- Load and display the first 20 digits from the Keras Handwriting MNIST dataset.
- Include demo code to load the dataset.
```python
from keras.datasets import mnist

# Load the MNIST dataset
(x_train, y_train), (x_test, y_test) = mnist.load_data()

# Display the first 20 images
# Add code snippet here

```

#### Day 19: Deep Learning Model Building on TensorFlow
- Build a deep learning model with the architecture (32x64x128x32x10) using TensorFlow.
- Train the model on the MNIST dataset from Day 18 and save the model.

#### Day 20: Model Hyperparameter Tuning for Improved Accuracy
- Load the model built on Day 19 and perform hyperparameter tuning to improve the model's accuracy. Use grid search or random search techniques to find the best hyperparameters.

