# Object Tracking Drone

This project is an implementation of an object tracking drone using Python and OpenCV. The drone is programmed to detect and track faces in real-time using a webcam feed.

## Prerequisites

- Python 3.x
- OpenCV
- NumPy

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/object-tracking-drone.git
    ```

2. Install the required dependencies:

    ```bash
    pip install opencv-python numpy
    ```

## Usage

1. Ensure that your webcam is properly connected to your system.
2. Navigate to the project directory.
3. Run the following command to start the object tracking drone:

    ```bash
    python object_tracking_drone.py
    ```

4. Once the program starts, it will open a window displaying the webcam feed with face detection and tracking.

## How it Works

1. The program captures frames from the webcam feed.
2. It detects faces in each frame using the Haar Cascade classifier.
3. Once a face is detected, the program calculates the centroid and area of the detected face.
4. Using proportional-integral-derivative (PID) control, the drone adjusts its movement to keep the detected face in the center of the frame.
5. The program continuously updates the movement commands sent to the drone based on the detected face's position and size.
6. The process continues until the user exits the program.

## Credits

This project was developed by Ruppikha Sree Shankar (https://github.com/ruppikha).
