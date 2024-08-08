# LED Control with Python, Mediapipe, and Arduino

This project demonstrates how to control five LEDs using hand gestures detected via a webcam, utilizing Python, Mediapipe, and Arduino. The setup tracks the number of visible fingertips and lights up corresponding LEDs connected to an Arduino.

## Project Components

- **Python**: Used for capturing video from a webcam, processing hand gestures using Mediapipe, and communicating with the Arduino via serial communication.
- **Mediapipe**: A framework for building multimodal machine learning pipelines, used here for hand tracking and fingertip detection.
- **Arduino**: A microcontroller that receives commands from Python to control the LEDs.

## Features

- **Hand Tracking**: Utilizes Mediapipe to detect and track hand movements in real-time.
- **Fingertip Detection**: Identifies which fingertips are pointing and sends this information to the Arduino.
- **LED Control**: Based on the number of visible fingertips, the Arduino turns on/off the corresponding LEDs.

## Requirements

- Python 3.x
- Arduino board (e.g., Uno or Nano)
- Five LEDs
- 220Ω resistors
- Mediapipe library
- OpenCV library
- PySerial library

## Installation

1. **Install Python packages**:
    ```sh
    pip install mediapipe opencv-python pyserial
    ```

2. **Set up the Arduino**:
    - Connect the anodes (long legs) of the LEDs to digital pins on the Arduino (e.g., pins 2, 3, 4, 5, and 6).
    - Connect the cathodes (short legs) of the LEDs to resistors (220Ω), and then connect the other ends of the resistors to the ground (GND) on the Arduino.

# DEMO Video
![Alt text]("C:\Users\rajat\Pictures\Gesture_Controlled_LED.mp4")

  
