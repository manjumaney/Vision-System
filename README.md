This assignment is about implementing classical as well as deep learning-based computer vision techniques using the Python programming language. The assignment has been completed using OpenCV and a pre-trained object detection model.

Harris Corner Detection

The Harris corner detection algorithm has been implemented, which is used to detect key points within an image where a significant change is observed. The corners have been highlighted using this algorithm, showing us the key points within an image.

Image Pyramid

An image pyramid has been created, which is a collection of scaled versions of an image. The image pyramid is used for multi-scale image analysis, and it is commonly used during object detection and feature extraction.

Feature Detection / Image Segmentation

One of the above-mentioned techniques has been implemented as per the assignment options:

- **SURF (Speeded-Up Robust Features):** This is used for detecting and describing distinctive features within an image. It is used for feature matching.

- **or**

- **Watershed Segmentation:** It is used for segmenting overlapping objects within an image. It separates the regions of an image based on pixel intensity and gradients.

SIFT Feature Extraction

The SIFT (Scale-Invariant Feature Transform) algorithm was developed for the detection of keypoints and the generation of feature descriptors that are scale and rotation invariant. The keypoints and their corresponding feature descriptors were plotted on the input image.

Object Detection Using YOLO

A pre-trained YOLO (You Only Look Once) model was employed for object detection. The pre-trained model was applied on five different images, and the detected objects were plotted using bounding boxes and class names.
