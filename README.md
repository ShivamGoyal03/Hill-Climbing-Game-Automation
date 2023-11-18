# Hand Gesture Recognition with MediaPipe and OpenCV

This project uses MediaPipe and OpenCV to recognize hand gestures from a video feed and simulate key presses. It's designed to allow users to control a game or application using hand gestures instead of traditional input methods.

## Project Description

The project uses a webcam to capture video and then processes each frame to detect hand landmarks using MediaPipe's Hands solution. The detected hand landmarks are used to determine whether certain gestures are being made. If a gesture is recognized, the script simulates a key press using the user defined module `directkeys`.

Currently, the script recognizes two gestures: a left swipe and a right swipe. These gestures are mapped to the left and right arrow keys, respectively. This allows the user to control a game or application by swiping their hand left or right.

## Dependencies

- cv2
- mediapipe
- time

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary dependencies using the command 

```
pip install -r requirements.txt
```

4. Run `main.ipynb`.

## How to Use

1. Ensure your webcam is set up and working.
2. Run `main.ipynb`.
3. Move your hand in front of the webcam to control the game or application.

## Key Bindings

- Open Fist - Acceleration
- Closed Fist - Brake

## Contributors

- [Shivam Goyal](https://www.linkedin.com/in/shivam2003/)
- [Saransh Shukla](https://www.linkedin.com/in/saransh2003)