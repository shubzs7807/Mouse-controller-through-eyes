# Mouse-controller-through-eyes

## Overview
The **Eye-Controlled Mouse** is an accessibility-focused project that enables users to control their computer's mouse using eye movements and blinks. This innovative system is designed for individuals with physical disabilities, allowing them to interact with digital devices without traditional input devices like a mouse or keyboard. 

The project leverages **computer vision** and **automation tools** to track facial landmarks and simulate mouse movements and clicks in real-time.

---

## Features
- **Real-Time Eye Tracking**: Tracks eye movement to control the mouse cursor.
- **Blink-Based Clicks**: Simulates mouse clicks using blinks detected through facial landmarks.
- **Accessible Interaction**: Provides a hands-free way to interact with computers.
- **Customizable**: Thresholds and other parameters can be adjusted for individual user needs.

---

## Technologies Used
- **Python**: The core programming language for implementation.
- **OpenCV**: For real-time video capture and frame processing.
- **MediaPipe**: To detect and track facial landmarks.
- **PyAutoGUI**: For automating mouse movements and clicks.

---

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.x
- Required Python Libraries:
  ```bash
  pip install opencv-python mediapipe pyautogui
