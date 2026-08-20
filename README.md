# Smart Vision Queue and Occupancy
[![SDAIA Academy Supported](https://img.shields.io/badge/Supported_By-SDAIA_Academy-007A3D?style=for-the-badge&logo=github)](https://github.com/SDAIAAcademy)

## Project Concept
The project automates the analysis of video footage in retail and restaurant environments by tracking human movement, behavior, and spatial distribution. Additionally, it monitors table occupancy rates and queue service speeds while strictly adhering to user privacy standards.

## Project Goals
* Optimize Operational Efficiency: Monitor peak hours and area congestion to manage staffing effectively.
* Enhance Customer Experience: Generate automated alerts when checkout queues overflow to minimize wait times.
* Protect Privacy: Apply automatic face-blurring algorithms to safeguard visitor privacy in compliance with regulations.
* Data-Driven Decision Making: Export periodic logs in standard formats (CSV) and generate interactive charts summarizing store analytics.

## The 5 Core Tasks
### Customer Counting:
Detect and track individuals passing through or present inside the store using tracking algorithms, continuously maintaining a total count.
### Heatmap Generation:
Render an interactive thermal overlay on the video frame to identify high-density and high-traffic areas.
### Face Anonymization / Blur:
Automatically detect the head and face region of every individual in the video and apply Gaussian Blur to protect personal data.
### Queue Alert System:
Monitor the designated queue area and trigger an immediate visual alert if the number of waiting customers exceeds the threshold (more than 5 people).
### Table/Booth Occupancy Detection:
Scan table and seating regions to dynamically determine their real-time status (Occupied / Available).

## Tools & Technologies
* Programming Language: Python
* YOLOv8 / Ultralytics
* OpenCV
* Pandas
* Matplotlib
* FFmpeg
