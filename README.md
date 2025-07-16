# 🚨 AcciGuard - Real-Time Accident Detection with SMS Alerts

> An intelligent system that detects road accidents from video streams using deep learning and immediately alerts emergency services via SMS.

---

## 📌 Why AcciGuard?

In road accidents, **every second counts**. The quicker an accident is detected, the faster help can arrive, reducing fatalities and injuries.  
**AcciGuard** was built with this urgency in mind. By analyzing video feeds from roads or dashcams, this system detects accidents in real-time and instantly sends an SMS alert to emergency services.

---

## 🔍 Key Features

- ✅ Real-time accident detection using 3D CNN (C3D) model
- 📦 Supports both **webcam** and **video file** input
- 🧠 Detects sudden vehicle stoppage, collisions, human fall/lift
- 🧪 Custom-trained on short clips of accidents vs normal traffic
- 🖥️ Simple Python-based GUI (Tkinter)
- 📲 Sends instant **SMS alerts** using Twilio API
- 📁 Optimized with frame skipping, GPU support, and class filtering

---

## 🛠️ Tech Stack

| Component | Tools Used |
|----------|-------------|
| Model    | PyTorch (3D CNN) |
| GUI      | Tkinter |
| Video Processing | OpenCV |
| SMS Alerts | Twilio API |
| Object Detection | YOLOv8 (optional module) |
| Platform | Google Colab / Local Python |

---

## 🧠 How It Works

1. 🎥 **Video Input** from webcam or file
2. 🧩 **Frame Extraction** and resizing
3. 🧠 **3D CNN model** analyzes motion patterns across clips
4. 🚨 **Detects accident events** based on sudden motion/stoppage
5. 📲 **SMS alert** is sent if accident is detected
6. 🖼️ Output video is saved with annotations (`Accident` / `Normal`)

---

## 🖥️ GUI Snapshot

> (Include a screenshot here, e.g. `assets/gui.png`)

