# Sign Language Gesture Tracker

## Overview

The **Sign Language Gesture Tracker** project is designed to track and display the coordinates of face and hand movements in real-time. By using computer vision techniques, the program detects and analyzes facial expressions and hand gestures, outputting the coordinates of key points to aid in sign language recognition. This can be used for educational purposes, accessibility tools, or further development of gesture-based technologies.

## Features

- **Real-time Tracking:** Track and visualize the position of your face and hands as you perform sign language gestures.
- **Coordinate Display:** Outputs the coordinates of key facial landmarks (eyes, nose, mouth) and hand movements (fingers, palm, wrist).
- **Interactive Visualization:** The program provides a visual representation of the detected landmarks overlaid on your live video feed.
- **Sign Language Recognition:** Can be extended for recognizing sign language gestures based on hand and facial coordinates.
- **Customizable for Various Applications:** Easily adaptable to build gesture-based control systems, accessibility tools, and more.

## Requirements

Before running the program, make sure you have the following installed:

- **Python 3.x** or later
- **OpenCV** for handling real-time video capture
- **MediaPipe** for hand and face landmark detection

### Dependencies

To install the required Python libraries, run the following:

```bash
pip install opencv-python mediapipe
```

## Usage

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/sign-language-gesture-tracker.git
```

### Step 2: Navigate to the project directory

```bash
cd sign-language-gesture-tracker
```

### Step 3: Run the program

```bash
python sign_language_tracker.py
```

The program will start a live video feed, and it will detect and display the coordinates of the face and hand landmarks in real-time.

### Example Output

Once the program is running, it will output coordinates for both face and hand landmarks, such as:

- **Face coordinates**: Eyes, nose, and mouth
- **Hand coordinates**: Wrist, fingertips, and other hand landmarks

For example:
```bash
Face Coordinates:
  Left Eye: (x: 0.35, y: 0.42)
  Nose: (x: 0.48, y: 0.55)
  Right Eye: (x: 0.61, y: 0.43)

Hand Coordinates:
  Thumb Tip: (x: 0.33, y: 0.58)
  Index Finger Tip: (x: 0.44, y: 0.61)
  Wrist: (x: 0.51, y: 0.64)
```

These coordinates can then be used for various purposes, such as:

- Gesture recognition for sign language interpretation
- Building a user interface with gesture control
- Educating users on sign language movements

## Customization

You can modify the program to:

- Recognize specific sign language gestures by analyzing the position and movement of key landmarks.
- Store the coordinates in different formats like JSON or CSV for further analysis.
- Integrate with other applications or frameworks to build gesture-based systems.
