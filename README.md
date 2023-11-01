# Hand Gesture-Based Virtual Mouse Control

![Virtual Mouse in Action](link_to_gif_or_image.gif)

This Python script enables real-time hand gesture-based control of the computer mouse using a webcam. It utilizes OpenCV, MediaPipe, and PyAutoGUI to track hand movements and simulate mouse actions.

## Features

- **Real-time Hand Tracking**: The script captures video from the default camera and uses the MediaPipe library to track your hand's movements.

- **Finger Detection**: It identifies the positions of the index and thumb fingers for precise control.

- **Virtual Mouse Movement**: The program maps hand positions to the screen's dimensions, allowing you to move the mouse cursor accurately.

- **Clicking Actions**: Perform left-click actions by pinching your thumb and index finger.

- **Customizable Thresholds**: You can adjust proximity thresholds for clicking and cursor movement sensitivity.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

## Getting Started

1. Clone this repository:
   ```sh
   git clone https://github.com/your_username/hand-gesture-mouse-control.git
   cd hand-gesture-mouse-control
2. Install the required Python libraries if you haven't already:
   ```
   pip install opencv-python mediapipe pyautogui
   ```
3. Run the script:
  ```
   python virtual_mouse.py
  ```
4. Ensure your webcam is correctly positioned to capture hand gestures.
5. Control your mouse using hand movements.
6. Close the script window to exit the virtual mouse control.

## Configuration

You can customize the following parameters in the script:
` thresholds ` for clicking and cursor movement sensitivity.

# Define sensitivity thresholds

click_threshold = 20
move_threshold = 100

##Acknowledgments

This project was inspired by the need for an intuitive and interactive way to control the computer mouse using hand gestures.

##Note

Don't forget to add your own image or GIF demonstrating the virtual mouse control in action.
