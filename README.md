# ML-algorithms-for-ADAS
Lane Detection and Traffic Sign Detection using Deep Learning and Computer Vision for Autonomous Driving Research Using CARLA Simulator

# Autonomous Vehicle Lane and Traffic Sign Detection

Welcome to the repository for our research and implementation on lane identification and traffic sign detection for autonomous vehicles. This project addresses the critical issues of unintentional lane departure and ignorance of traffic signs, which are major contributors to motor vehicle collisions globally.

## Overview

Autonomous vehicles rely on accurate and robust lane and traffic sign detection systems to navigate safely. This project proposes a solution using semantic segmentation and object detection models, specifically employing Convolutional Neural Networks (CNN) such as SegNet and the You Only Look Once (YOLO) algorithm.

<img width="1023" alt="Screenshot 2023-08-17 at 2 46 34 PM" src="https://github.com/hithaishisurendra/ML-algorithms-for-ADAS/assets/114680442/9b2628ec-0b3d-46f6-bb60-d62114270499">
<img width="684" alt="Screenshot 2023-08-17 at 2 48 04 PM" src="https://github.com/hithaishisurendra/ML-algorithms-for-ADAS/assets/114680442/eace61eb-311b-40c2-9305-72e37b0c700f">


## Implementation

To tackle the challenges posed by dynamic and adverse driving conditions, we have leveraged the CARLA simulator to set up a virtual environment for testing. This allows us to simulate various urban driving scenarios and assess the performance of our models under different constraints.

### Models Used

1. **SegNet for Lane Detection:**
   - Mean Average Precision (mAP): 93.33%
   - Accuracy: 94.80%
   - F-score: 93.42%
   - Error Rate: 5.20%

2. **YOLO Algorithm for Traffic Sign Detection:**
   - Mean Average Precision: 93.67%
   - Accuracy: 95.56%
   - F-score: 93.16%
   - Error Rate: 4.44%

We will be uploading the two datasets used and code as soon as possible.

Thank you for exploring our project! 🚗🔍
