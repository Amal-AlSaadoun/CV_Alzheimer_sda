# CV_Alzheimer_sda
An Ultralytics YOLO instance-segmentation pipeline that classifies MRI brain scans into four Alzheimer's severity stages (Non/VeryMild/Mild/ Moderate) and demonstrates real-time queue analytics on video using region-based tracking.


 Project Overview:
This project applies computer vision to two use cases built on the
Ultralytics YOLO framework:

1. **Medical imaging classification** — an instance-segmentation model
   (YOLOv8n-seg) fine-tuned on an MRI brain-scan dataset (Roboflow
   Universe) to segment and classify Alzheimer's severity into four
   stages: Non-Demented, Very Mild, Mild, and Moderate.
2. **Real-world video analytics** — a queue-occupancy monitoring
   pipeline that tracks people in a defined region of interest in
   real time and raises an alert when occupancy exceeds a threshold.

This project was completed as the capstone for the "Computer Vision for
Developers with Ultralytics" training program, delivered by SDAIA
Academye.

# Training program: SDAIA Academy — Computer Vision for Developers (link: https://github.com/SDAIAAcademy)

# 🎬 Video Analytics Demo

>**Note:** Video playback is not supported directly inside .ipynb; A video of the queue analytics and tracking has been uploaded to this repository.
