# 🎨 Air Canvas – Hand Gesture Based Virtual Drawing Application

Air Canvas is a computer vision–based interactive drawing application that allows users to draw, erase, and select colors **in the air using hand gestures**, without touching the screen. The application uses a webcam to track hand movements in real time and converts finger gestures into drawing actions on a virtual canvas.

---

## 🚀 Project Overview

This project uses **OpenCV** for image processing and **MediaPipe Hand Tracking** for detecting hand landmarks. By analyzing finger positions, the system intelligently switches between drawing mode and color selection mode, providing a smooth and intuitive user experience.

---

## ✋ Features

- 🖐️ Real-time hand gesture recognition  
- ✍️ Draw using only your index finger  
- 🎨 Select different colors using gestures  
- 🧽 Eraser mode to remove drawings  
- 🧹 Clear canvas using keyboard shortcut  
- 📷 Webcam-based interaction  
- ⚡ Smooth and responsive drawing  

---

## 🧠 Gesture Controls

| Gesture | Action |
|------|------|
| Index finger up | Drawing mode |
| Index + middle finger up | Color selection mode |
| Touch top color bar | Select color |
| Press `C` | Clear canvas |
| Press `Q` | Quit application |

---

## 🛠️ Technologies Used

- **Python 3.10**
- **OpenCV**
- **MediaPipe**
- **NumPy**

---

## 📂 Project Structure
aircanvas/
│
├── air_canvas.py # Main application file
├── .gitignore # Ignored files and folders
├── venv/ # Virtual environment (not pushed to GitHub)
└── README.md # Project documentation


---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone <your-repo-link>
cd aircanvas

2️⃣ Create a virtual environment
py -3.10 -m venv venv

3️⃣ Activate the virtual environment

Windows (PowerShell):

.\venv\Scripts\activate

4️⃣ Install required dependencies
pip install opencv-python mediapipe==0.10.9 numpy

5️⃣ Run the application
python air_canvas.py

📌 Use Cases

Virtual whiteboard

Touch-free drawing system

Educational demonstrations

Computer vision mini-project

Gesture-controlled UI applications

🎯 Learning Outcomes

Understanding of real-time computer vision

Hands-on experience with MediaPipe hand landmarks

Gesture-based interaction design

Integration of OpenCV with ML-based tracking

🌟 Future Enhancements

Save drawings as images

Add more colors and brush sizes

Gesture-based clear and save options

Multi-hand support

Improved UI and performance optimization
