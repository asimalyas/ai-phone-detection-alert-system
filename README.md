# 📵 AI Phone Detection & Alert System

Real-time mobile phone detection system using **YOLOv8** and **Computer Vision** that triggers an **audio alert** whenever a phone is detected through a webcam.

---

## 🚀 Features

- Real-time phone detection using webcam
- YOLOv8 Nano model for fast performance
- Audio alert system with cooldown timer
- Frame skipping for smooth video & higher FPS
- Red bounding box and warning message on detection
- Lightweight and easy to run

---

## 🧠 How It Works

1. Webcam captures live video frames  
2. YOLOv8 detects objects in selected frames  
3. If a **cell phone** is detected:
   - Red bounding box is drawn
   - Warning text is displayed
   - Audio alert is triggered
4. Cooldown timer prevents repeated alerts

---

## ⚙️ Technologies Used

- **Python**
- **YOLOv8 (Ultralytics)**
- **OpenCV**
- **Pygame**
- **NumPy**

---

## 🛠 Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ai-phone-detection-alert-system.git
cd ai-phone-detection-alert-system
