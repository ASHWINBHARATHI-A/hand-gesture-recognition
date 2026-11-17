# Hand Gesture Recognition V1

A real-time computer vision project that detects and recognizes hand gestures using a webcam.

## Overview

Hand Gesture Recognition uses computer vision and hand landmark detection to identify different hand gestures in real time. The project tracks hand movements through a webcam and classifies gestures based on detected finger positions.

**Version:** 1.0  
**Project Type:** Computer Vision / AI  
**Status:** Initial Release

## Features

- Real-time hand detection using a webcam
- Hand landmark tracking
- Recognition of multiple hand gestures
- Gesture classification based on finger positions
- Gesture smoothing to reduce incorrect detections
- Live visual feedback
- Optional keyboard automation

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Webcam access and image processing |
| MediaPipe | Hand landmark detection |
| PyAutoGUI | Optional keyboard automation |

## Supported Gestures

| Gesture | Action |
|---|---|
| Fist | Play / Pause |
| Peace Sign | Next Slide |
| Pointing Finger | Previous Slide |
| Thumbs Up | Volume Up |
| Open Palm | Idle |

*Keyboard actions are available when the optional action mode is enabled.*

## Project Structure

```text
Hand-Gesture-Recognition/
│
├── hand_gesture.py
├── hand_landmarker.task
├── requirements.txt
├── README.md
├── .gitignore
├── LICENSE
│
├── assets/
│   └── screenshots/
│
└── docs/
    └── PROJECT_OVERVIEW.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ASHWINBHARATHI-A/hand-gesture-recognition.git
```

### 2. Open the Project

```bash
cd hand-gesture-recognition
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Project

```bash
python hand_gesture.py
```

## How It Works

1. The webcam captures live video.
2. OpenCV processes the video frames.
3. MediaPipe detects the hand and identifies its 21 landmarks.
4. The system analyzes finger positions.
5. A gesture classification algorithm identifies the current gesture.
6. Gesture smoothing helps avoid unstable classifications.
7. Optional keyboard actions execute based on recognized gestures.

## Future Improvements

- [ ] Support for two-hand gesture recognition
- [ ] Custom gesture training
- [ ] Air writing using finger movements
- [ ] Mouse cursor control
- [ ] Virtual keyboard
- [ ] Gesture-controlled media player
- [ ] Improved gesture accuracy
- [ ] GUI-based gesture configuration

## Version History

**V1.0 – Initial Release**
- Webcam-based hand tracking
- Real-time gesture recognition
- Multiple predefined gestures
- Optional keyboard automation

## Author

**Ashwin Bharathi A**

Computer Science and Engineering  
Sri Krishna College of Engineering and Technology (SKCET)

GitHub: [ASHWINBHARATHI-A](https://github.com/ASHWINBHARATHI-A)

---

*Built as a hands-on project to explore Computer Vision, Python, and Human-Computer Interaction.*
