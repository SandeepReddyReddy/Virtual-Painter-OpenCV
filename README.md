# Virtual Painter using OpenCV & MediaPipe
A gesture-controlled virtual drawing application that allows users to draw on a digital canvas using hand gestures captured via a webcam.

## Problem Statement
Traditional drawing applications require physical input devices such as a mouse or stylus.  
This project aims to create a touchless drawing system using computer vision and hand gesture recognition.

## Objectives
- Detect hand landmarks in real time
- Enable drawing using finger gestures
- Allow color selection and erasing
- Save drawings only when valid content exists
- Provide user feedback through on-screen notifications

## Technologies Used
- Python
- OpenCV
- MediaPipe (Hands)
- NumPy

## Workflow
1. Capture live video using webcam
2. Detect hand landmarks using MediaPipe
3. Identify finger gestures
4. Perform actions:
   - Draw
   - Select color
   - Erase
   - Save drawing
5. Display output in real time

## Features
- Real-time hand gesture detection
- Draw using index finger
- Color selection using index + middle finger
- Eraser functionality
- Save drawings with on-screen confirmation
- Prevents saving empty canvas
- Touchless interaction

## Gesture Mapping
Display Color labels and Eraser on the top
☝️ Index only --> Drawing Mode                
✌️ Index + Middle --> Color/Eraser Selection Mode
✋ All five fingers UP --> No action
✊ All closed --> No action
Press key "S" --> Saves current canvas as drawing_1.png, drawing_2.png...
Predd key "Q" --> Stops frame reading and Releases the webcam


Clone the repository:
git clone https://github.com/SandeepReddyReddy/Virtual-Painter-OpenCV
