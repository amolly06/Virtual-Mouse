# Project Title: Virtual Mouse

## Description
**Virtual Mouse** is a Python application that enables users to control their computer's mouse cursor using hand gestures detected via a webcam. This project utilizes MediaPipe for hand tracking and PyAutoGUI for simulating mouse movements and clicks. The application focuses on providing an intuitive way to navigate and interact with a computer interface without the need for a physical mouse.

## Features
- Hand tracking using MediaPipe.
- Control mouse cursor movements with hand gestures.
- Perform left, right, and double-clicks using specific gestures.
- Take screenshots using a designated gesture.
- Adjustable gesture sensitivity and recognition thresholds.

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI
- pynput
- numpy

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/virtual-mouse.git
   cd virtual-mouse
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Files
- `virtualMouse.ipynb`: Jupyter notebook containing the main application logic and gestures for controlling the mouse.
- `util.py`: Utility functions used within the application for gesture recognition and processing.

## Usage
1. Run the application:
   ```bash
   python virtualMouse.ipynb
   ```

2. Allow the application to access your webcam. Ensure you are in front of the camera and that your hand gestures are visible.

3. Use the following gestures to control the mouse:
   - **Move cursor**: Position your index finger in the camera view.
   - **Left Click**: Pinch your thumb and index finger together.
   - **Right Click**: Extend your thumb and pinch your index finger.
   - **Double Click**: Quickly pinch your thumb and index finger twice.
   - **Screenshot**: Pinch your thumb and index finger and hold for a moment.

## Acknowledgements
- [MediaPipe](https://google.github.io/mediapipe/) for hand tracking capabilities.
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) for simulating mouse actions.
- OpenCV for image processing.
