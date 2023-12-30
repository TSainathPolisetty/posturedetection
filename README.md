# Lying Posture Detection using IMU Sensor and Machine Learning

### Introduction
This project focuses on developing a real-time posture monitoring system using an IMU sensor embedded in an Arduino board. It aims to leverage machine learning to distinguish various postures and implement these capabilities in a microcontroller for real-time predictions.

### Project Explanation
- **Objective**: Design a system capable of real-time posture monitoring using a combination of IMU sensors and machine learning.
- **Process**: Involves data collection using IMU sensors, data processing and labeling, training a machine learning model, and integrating this model into an Arduino microcontroller for posture detection.
- **System Interaction**: Interfaces with devices like laptops or smartphones for command input and data display.

### Algorithm and Model Development
- **Initial Approach**: Began with an LSTM model, transitioning to a GRU model due to deployment challenges on the microcontroller.
- **Final Model**: Simple Dense Feed-forward Neural Network, optimized for computational efficiency and accuracy.
- **Deployment**: Faced challenges in tensor loading and data normalization, resolved by custom functions and constants derived from training data statistics.

## Demonstration - Click on the image to play video
[![Posture Detection Using ML and Arduino Nano 33 BLE Sense Demonstration](https://img.youtube.com/vi/xbyrc6f-VAA/maxresdefault.jpg)](https://youtu.be/xbyrc6f-VAA)

### Results & Analysis
- **Accuracy and Performance**: Demonstrated high accuracy in real-time predictions, particularly with accelerometer data.
- **Comparative Analysis**: Showed consistent proficiency between test data and real-time predictions, highlighting the model's reliability and adaptability.

### Conclusions and Future Work
- **Summary**: Successfully developed a system for real-time posture detection using an IMU sensor and machine learning.
- **Challenges and Future Directions**: Addressing orientation insensitivity and sensor variability, and refining the model for enhanced real-time performance.


