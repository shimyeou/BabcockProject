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

![fatigue_events_over_time_20250625_133130](https://github.com/user-attachments/assets/9c2ffada-8508-425f-abe8-fcb496502c85)
![fatigue_event_counts_20250625_133130](https://github.com/user-attachments/assets/2ddd0edf-2e4a-400c-90da-b2d9b5fe5ebe)
