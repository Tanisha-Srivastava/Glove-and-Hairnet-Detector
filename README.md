# Safety Detection of Workers using YOLOv8

This project is a real-time **worker safety detection system** built using **YOLOv8**, **OpenCV**, and a modern **CustomTkinter GUI**.  
It uses a webcam feed to detect specific safety-related classes such as **Front Palm**, **Back Palm**, and **Hair**, and tracks the duration for which these classes are continuously detected.

The application is designed to be simple, interactive, and suitable for academic projects, demos, or safety monitoring prototypes.

---

## ✨ Features

- 📷 Live webcam-based object detection
- 🤖 YOLOv8 custom-trained model support
- 🖐️ Detection of custom classes:
  - Front_Palm
  - Back_Palm
  - Hair
- ⏱️ Real-time detection timer
- 🖥️ Modern dark-themed GUI using CustomTkinter
- 🎯 Bounding box visualization on detected objects
- ⌨️ Press **Q** to stop detection and return to home screen

---

## 🛠️ Technologies Used

- Python 3.x
- YOLOv8 (Ultralytics)
- OpenCV
- CustomTkinter
- Pillow (PIL)

---
## 🚀 How It Works

1. The user launches the application.
2. A **Home Screen** appears with a “Start Detection” button.
3. On clicking the button:
   - Webcam access is initiated.
   - YOLOv8 performs real-time object detection.
4. If any target class (`Front_Palm`, `Back_Palm`, or `Hair`) is detected:
   - The detection timer starts.
5. Bounding boxes and class labels are rendered on the live video feed.
6. Press **Q** to stop detection and return to the home screen.

---
