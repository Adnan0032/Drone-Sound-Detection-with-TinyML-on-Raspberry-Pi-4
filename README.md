# Drone-Sound-Detection-with-TinyML-on-Raspberry-Pi-4
This project leverages TinyML to deploy a lightweight machine learning model on a Raspberry Pi 4 to detect drones based on their audio signatures. The system processes sound input, extracts audio features, and classifies the presence of drones in real time.
## Features:
Audio Feature Extraction: Uses Mel-frequency cepstral coefficients (MFCCs) or spectrograms for sound analysis.

Real-Time Detection: Processes audio data on-device for immediate results.

Resource Efficient: Optimized for deployment on resource-constrained hardware like the Raspberry Pi 4.

Scalable Application: Can be adapted for environmental monitoring, security, or anti-drone systems.
## Technologies Used:
Python: For preprocessing and inference.

TensorFlow Lite: To run the optimized machine learning model.

Raspberry Pi 4: As the edge device for deployment.

Microphone Module: For capturing audio input.
## Getting Started:
Prepare the Raspberry Pi 4 with the required dependencies.

Train or use the pre-trained drone detection model.

Deploy the model using TensorFlow Lite.

Connect a microphone for audio input and run real-time detection.
