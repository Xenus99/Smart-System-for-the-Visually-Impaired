# Smart System for the Visually Impaired

## Overview
This project aims to assist visually impaired individuals by detecting obstacles around them in real-time. Using TensorFlow and RCNN/SSD algorithms, the system identifies objects in the camera's field of view. The system then calculates the distance based on the object's size and provides audio feedback, such as "Chair to your left at 2 meters", to guide the user.

## Libraries Used
- **TensorFlow**: For object detection using the RCNN and SSD models.
- **OpenCV**: For real-time camera input and image processing.

## Features
- Object detection in real-time using TensorFlow.
- Distance calculation based on object size and position.
- Audio feedback for obstacle detection (e.g., "Chair to your left at 2 meters").

## Usage
1. Clone the repository.
2. Install necessary dependencies:
    ```bash
    pip install tensorflow opencv-python
    ```
3. Run the system with your camera:
    ```bash
    python run_system.py
    ```
