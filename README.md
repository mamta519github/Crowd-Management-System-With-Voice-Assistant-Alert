# Crowd-Management-System-With-Voice-Assistant-Alert

This project demonstrates a *Crowd Management System* powered by *OpenCV* and *deep learning-based object detection* to monitor and manage crowd density in real time. It uses video feeds (live or recorded) to detect people and analyze crowd levels, helping ensure safety and avoid overcrowding.

## 🚀 Features

- Real-time crowd detection
- Person detection using deep learning models (YOLO / MobileNet-SSD / Haar Cascade)
- Area density estimation
- Alerts on crowd threshold breaches
- Works on video files or webcam streams

## 🛠 Technologies Used

- Python 3.x  
- OpenCV  
- NumPy  
- Pre-trained Object Detection models (YOLOv3 / MobileNet-SSD)
- Jupyter Notebook (for development & visualization)

## 🗂 Project Structure

Crowd_Management/
├── Crowd_Management.ipynb      # Main notebook with code
├── models/                     # Pre-trained detection models (YOLOv3, MobileNet, etc.)
├── test_videos/                # Sample input videos
├── utils/                      # Helper scripts and modules
└── README.md                   # Project documentation

Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/mamta519github/crowd-management.git
cd crowd-management
Create Virtual Environment (Optional but Recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Install Required Packages

bash
Copy
Edit
pip install -r requirements.txt
Download Pre-trained Models

