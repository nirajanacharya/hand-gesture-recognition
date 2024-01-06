# Hand Gesture Recognition with Emotion

## Overview
This project implements a real-time hand gesture recognition system with emotion detection. It recognizes various hand gestures and associates them with corresponding emotions.

## Features
- Recognizes hand gestures including peace, thumbs up, thumbs down, call me, stop, rock, live long, fist, smile, etc.
- Emotion detection based on hand gestures.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- Mediapipe
- TensorFlow
- [mediapipe Hands](https://google.github.io/mediapipe/solutions/hands.html) (for hand landmark detection)
- trained gesture recognizer model (`mp_hand_gesture`) and class names file (`gesture.names`)
![WhatsApp Image 2024-01-06 at 5 14 47 PM](https://github.com/NirajanAcharya666/hand-gesture-recognition/assets/87110903/b892306c-8732-491c-b07a-58dfd5aa6943)
## Usage
1. Install the required dependencies using:
   ```bash
   pip install opencv-python numpy mediapipe tensorflow

