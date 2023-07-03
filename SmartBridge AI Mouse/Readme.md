# Gesture Controlled Virtual Mouse

This project aims to implement a gesture-controlled virtual mouse using OpenCV, Mediapipe, PyAutoGUI, and other essential Python libraries. This software leverages real-time hand gesture recognition using Mediapipe hands to detect hands' motion and position.

## Main Features

- Recognizes hand gestures from camera input.
- Maps gestures to specific functions such as controlling mouse movements, clicks, right-clicks or double-clicks, making sound, and scrolling up/down or right/left.
- Provides options for custom mappings of gestures.
- Works with multi-hand input by detecting the predominant hand.
- Uses Mediapipe's pose estimation to localize hand and finger landmarks and track their movement.
- Applies dampening to stabilize mouse movements.


## Requirements

- Python 3.x
- OpenCV
- Mediapipe
- PyAutoGUI
- Flask


## Usage

1. Run the application:
   
```bash
flask run
```

2. Open your browser and navigate to http://localhost:5000 to view the live video feed and interact with the application.

3. Perform hand gestures to control the virtual mouse.


