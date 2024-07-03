# Waste-Classifier

## Overview
This project focuses on automating waste segregation using computer vision and hardware integration. It employs OpenCV for image processing to classify different types of waste, and Arduino with a servo motor to automate the opening of respective waste bins based on the classification.

## Key Features
- **Image Classification:** Utilizes OpenCV in Python to classify waste types such as plastic, paper, metal, etc., from captured images.
- **Hardware Integration:** Arduino is used to control a servo motor mechanism that opens specific bins corresponding to the detected waste type.
- **Real-time Processing:** Capable of real-time classification and immediate action using the integrated hardware setup.

## Technologies Used
- **Python:**
  - OpenCV for image processing and classification.
- **Arduino:**
  - Controls servo motor based on signals from Python.
- **Servo Motor:** Mechanism to open/close respective waste bins.