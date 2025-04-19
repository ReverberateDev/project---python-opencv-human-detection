# Human Detection with OpenCV

This project demonstrates human detection in real-time using OpenCV's HOGDescriptor and a pre-trained SVM detector. The program captures video from a connected camera, detects humans in the frames, and highlights them with bounding boxes.

## How It Works

1. The program initializes OpenCV's HOGDescriptor and sets the default people detector.
2. It captures video from the default camera (camera index 1).
3. Each frame is resized to 640x480 and converted to grayscale for processing.
4. The HOG detector identifies humans in the frame, and bounding boxes are drawn around detected individuals.
5. The processed video is displayed in a window. Press `q` to quit the program.

## Requirements

- Python 3.x
- NumPy 1.26.4
- OpenCV 4.10.0.82

## Setup Instructions

1. Clone the repository to your local machine.
2. Create a virtual environment and activate it.
3. Install the required dependencies using `pip` and the `requirements.txt` file.
4. Run the `human_detection.py` script to start the program.

## Usage

1. Ensure a camera is connected to your system.
2. Run the script and observe the real-time human detection.
3. Press `q` to exit the program.

## Files in the Project

- `human_detection.py`: The main script for human detection.
- `requirements.txt`: Lists the required Python packages.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## Notes

- The program uses camera index 1. If your camera is not detected, try changing the index in the `cv2.VideoCapture()` function.
- Ensure the required Python packages are installed before running the script.
- The detection accuracy may vary depending on lighting conditions and camera quality.uman Detection with OpenCV

This project demonstrates human detection in real-time using OpenCV's HOGDescriptor and a pre-trained SVM detector. The program captures video from a connected camera, detects humans in the frames, and highlights them with bounding boxes.

How It Works:

The program initializes OpenCV's HOGDescriptor and sets the default people detector.
It captures video from the default camera (camera index 1).
Each frame is resized to 640x480 and converted to grayscale for processing.
The HOG detector identifies humans in the frame, and bounding boxes are drawn around detected individuals.
The processed video is displayed in a window. Press 'q' to quit the program.
Requirements:

Python 3.x
NumPy 1.26.4
OpenCV 4.10.0.82
Setup Instructions:

Clone the repository to your local machine.
Create a virtual environment and activate it.
Install the required dependencies using pip and the requirements.txt file.
Run the human_detection.py script to start the program.
Usage:

Ensure a camera is connected to your system.
Run the script and observe the real-time human detection.
Press 'q' to exit the program.
Files in the Project:

human_detection.py: The main script for human detection.
requirements.txt: Lists the required Python packages.
.gitignore: Specifies files and directories to be ignored by Git.
Notes:

The program uses camera index 1. If your camera is not detected, try changing the index in the cv2.VideoCapture() function.
Ensure the required Python packages are installed before running the script.
The detection accuracy may vary depending on lighting conditions and camera quality.