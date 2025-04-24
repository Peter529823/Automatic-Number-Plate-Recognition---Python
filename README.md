# Automatic-Number-Plate-Recognition---Python

**Goal** Use python with OpenCV and EasyOCR to perform automatic number plate recognition.

**Steps**
1. Install and Import Dependencies.
2. Read in Image, Grayscale and blur.
3. Apply filter and find edges for localization.
4. Find Contours and apply mask
5. EasyOCR to read text
6. Render Result.

**Key Dependencies Used**
PyTorch is an open-source machine learning library based on the Torch library, used to build models for applications such as deep learning, computer vision, image recognition, and natural language processing. Pytorch is designed to be flexible and provides stability. We need Pytorch installed to facilitate using EasyOCR. 
CV2 - OpenCV is a powerful library for image processing and computer vision tasks. It is used for reading and writing images, image manipulation feature detection, and object detection. 
Matplotlib - Matplotlib is a comprehensive plotting library for creating static, animated, and interactive visualizations in Python.
NumPy – NumPy is a fundamental library for scientific computing in Python.
Imutils - A Python library built on top of OpenCV, designed to make basic image processing operations simpler and more convenient.
EasyOCR - A Python package for detecting and extracting text from images such as photos or scanned documents. EasyOCR is a reliable tool that makes detecting and extracting text from images simple. 
