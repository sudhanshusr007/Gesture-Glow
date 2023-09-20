# GestureGlow: Hand-Controlled Screen Brilliance

GestureGlow is a project that allows users to control screen brightness using hand gestures. It utilizes the capabilities of computer vision and OpenCV to detect hand gestures and adjust screen brightness accordingly.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

GestureGlow is a unique project that uses computer vision techniques, specifically using the Mediapipe library and OpenCV, to detect hand gestures. The detected hand gestures are then mapped to screen brightness adjustments, providing an intuitive and interactive way to control screen brightness.

## Features

- Hand gesture recognition for brightness control.
- Real-time adjustments of screen brightness based on hand gestures.
- Efficient and responsive interaction for a seamless user experience.

## Requirements

Make sure you have the following dependencies installed:

- `mediapipe`
- `cv2` (OpenCV)
- `numpy`
- `screen_brightness_control`
- `math` (hypot function)

You can install these using pip:
```bash
pip install mediapipe cv2 numpy screen_brightness_control
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/GestureGlow.git
   cd GestureGlow
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main script to start the application:
   ```bash
   python main.py
   ```

2. Follow the on-screen instructions to calibrate and use hand gestures for controlling screen brightness.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

