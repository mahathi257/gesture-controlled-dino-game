# Gesture-Controlled Dino Game

This project demonstrates a gesture-controlled Dino game using OpenCV for gesture detection and ctypes for simulating key presses on Windows.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Gesture-Controlled Dino Game uses your webcam to detect hand gestures and control the Dino character to jump over obstacles. The game combines computer vision and key press simulation to create an interactive gaming experience.

## Features

- Real-time hand gesture detection using OpenCV
- Simulated key presses using ctypes
- Pause/resume functionality with a specific hand gesture

## Installation

To get started, clone the repository and install the required dependencies.


git clone https://github.com/mahathi257/gesture-controlled-dino-game.git
cd gesture-controlled-dino-game
pip install -r requirements.txt

## Usage
Run the main script to start the game.

python main.py
Make sure your webcam is connected and properly configured. Use hand gestures to control the Dino.

## How It Works
1.Video Capture: OpenCV captures video from the webcam.
2.Hand Detection: The script uses the cvzone library's HandDetector module to detect hand gestures.
3.Gesture Recognition: Based on the detected hand gestures, the script recognizes specific gestures.
4.Key Press Simulation: The recognized gestures are mapped to key presses using ctypes to simulate space key presses.

## Main Components
-main.py: Main script that integrates gesture detection and key press simulation.
-gesture_detection.py: Handles video capture and gesture recognition using OpenCV and cvzone.
-directkeys.py: Contains functions to simulate key presses using ctypes.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any features, bug fixes, or enhancements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


This README includes the installation instructions for `cvzone` and provides a comprehensive guide on how to set up and use the project.

