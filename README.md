# Automated Number Plate Recognition (ANPR) using OpenCV and Camera

## Overview

This project is an Automated Number Plate Recognition (ANPR) system implemented in a Jupyter Notebook using OpenCV and a camera. The system is designed to automatically detect license plates in images or video streams captured by the camera and extract the alphanumeric characters for further processing.

![ANPR Demo](demo.gif)

## Features

- **License Plate Detection:** Automatically detect license plates in images or video streams.
- **Character Segmentation:** Segment the alphanumeric characters from the detected license plates.
- **Character Recognition:** Recognize and extract the alphanumeric characters from the segmented regions.
- **Real-time Processing:** Perform ANPR in real-time using a connected camera.

## Installation

To set up this ANPR system, follow these steps:

1. Clone or download this repository to your local machine.
2. Ensure you have the necessary dependencies installed, including OpenCV and Jupyter Notebook.

## Usage

1. Open the Jupyter Notebook file (`anpr.ipynb`) in Jupyter Notebook or JupyterLab.
2. Ensure your camera is connected to your system.
3. Follow the instructions and run each cell in the notebook to start the ANPR system.
4. The system will begin processing the video stream from the camera, detecting license plates, and recognizing the characters.

## Configuration

- **Camera Settings:** Adjust camera parameters such as resolution, frame rate, etc., in the notebook as needed.
- **Character Recognition Model:** Train or fine-tune the character recognition model for better accuracy.

