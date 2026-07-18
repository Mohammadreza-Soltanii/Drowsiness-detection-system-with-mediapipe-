# Real-Time Lightweight Drowsiness Detection System

This repository features a lightweight, zero-latency driver drowsiness detection system built using Computer Vision and geometric facial features.

## 💡 System Overview (High FPS / Zero Latency)
Unlike heavy deep learning models, this system relies purely on facial landmarks to calculate the **EAR (Eye Aspect Ratio)** dynamically using MediaPipe Face Mesh. 

- **Pros:** Extremely fast, zero latency, runs smoothly on any CPU or low-end hardware.
- **Key Feature:** Uses precise mathematical thresholds to track eye states and trigger the `DROWSY ALERT!`.

## 🛠 Tech Stack
- Python 3.12
- MediaPipe (Face Mesh landmarks)
- OpenCV (cv2 for webcam pipeline)
- NumPy

🗺️ Future Roadmap
I am actively expanding this repository into a production-ready automated ecosystem:
📊 Advanced Data Cleaning Portfolio: Adding a dedicated pipeline showcasing data preprocessing and feature engineering using Pandas.
🔌 n8n Automation & Webhooks: Transitioning the alert trigger from local execution to a cloud-based automation workflow via n8n.
📢 Telegram Bot Integration: Connecting the system to a Telegram Bot (via n8n) to send instant push notifications when a drowsiness alert is triggered.
