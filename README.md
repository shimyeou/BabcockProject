## Background
Babcock is a global defence and engineering company that provides critical services to civil and military sectors, including a range of maritime sustainment services. Worker fatigue within these fast-paced environments poses a significant risk in decision making capability, and resultant worker safety. While training exists, there’s no effective way to monitor fatigue in real time. This project proposes a proof-of-concept tool using computer vision and machine learning to address this gap.

## Problem
Console operators and maintenance personnel often work long, repetitive hours in physically and mentally unstimulating environments, leading to increased risks of fatigue. This fatigue can significantly impair decision making, reduce alertness, and compromise safety and performance. Current assessment methods rely mainly on one-time, pre-shift questionnaires or rostering assumptions, offering limited insight into real-time fatigue levels during operations. Particularly in maritime maintenance and sustainment, where strict adherence to checklists is vital, the absence of continuous fatigue monitoring poses a risk to both worker wellbeing and operational safety.

## Key Features
1. Eye aspect ration (EAR)
2. Mouth aspect ratio (MAR)
3. DeepFace for face recognition
4. Visual indicators and alerts for drowsy behavior
5. Long session monitoring with time-based filtering
6. Automic generation aof fatigue event logs and excel reports

## Technologies Used
Python, OpenCV, dlib, DeepFace, YOLOv5

## Goals
- Demonstrates how a computer vision system can monitor worker fatigue in real time 
- Provides insight into onset fatigue characteristics and how they can be analyzed
- Shows how fatigue onset can be actively detected using visual indicators like eye and facial cues
- Potential integration with other systems, such as dashboards or wearable sensors

## Reports 
See the detailed `Comparison_Report`for an in-depth analysis of the accuracy between two methods. Full codes for each method can be found in the `MAR_EAR_Detection` and `YOLOv5_Detection` folders. Some example log file produced by these methods is also available in the `Reports` folder.
