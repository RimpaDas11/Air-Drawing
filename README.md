# 🎨 Air Drawing – Virtual Painter

<div align="center">

### Draw in the Air Using Hand Gestures and Computer Vision

A real-time gesture-controlled drawing application that transforms hand movements into digital artwork using Computer Vision and Hand Tracking.

---

**Python • OpenCV • MediaPipe • Computer Vision • Hand Tracking**

</div>

---

# 🌟 Overview

Air Drawing is a Computer Vision-based application that allows users to draw on a virtual canvas using hand gestures captured through a webcam.

Built using OpenCV and MediaPipe, the system tracks hand landmarks in real time and converts finger movements into digital strokes. Users can select colors, erase drawings, and interact with the canvas without touching any physical input device.

This project demonstrates the practical implementation of gesture recognition, hand tracking, and real-time image processing using modern Computer Vision techniques.

---

# 🎯 Problem Statement

Traditional drawing applications require physical input devices such as a mouse, stylus, or touchscreen.

The objective of this project is to create a touchless drawing system that enables users to:

* Draw using hand gestures
* Interact without physical contact
* Explore gesture-based interfaces
* Experience real-time Computer Vision applications

---

# 🚀 Key Features

### ✋ Real-Time Hand Tracking

Detects and tracks hand landmarks using MediaPipe.

### 👆 Gesture-Based Drawing

Draw naturally using index finger movements.

### ✌️ Selection Mode

Use multiple fingers to switch between tools and colors.

### 🌈 Multiple Color Options

Choose different colors for drawing.

### 🧽 Eraser Tool

Remove unwanted drawings easily.

### 🗑️ Clear Canvas

Reset the entire drawing board instantly.

### 📷 Webcam-Based Interaction

No additional hardware required.

### ⚡ Smooth Drawing Experience

Optimized for real-time performance and responsiveness.

---

# 🏗️ System Architecture

```text
Webcam Input
      │
      ▼
Video Frame Capture
(OpenCV)
      │
      ▼
Hand Detection
(MediaPipe)
      │
      ▼
Landmark Tracking
      │
      ▼
Gesture Recognition
      │
      ▼
Drawing Engine
      │
      ▼
Virtual Canvas Output
```

---

# 📂 Project Structure

```text
Air-Drawing/
│
├── main.py
├── handTracker.py
├── requirements.txt
├── images/
└── README.md
```

---

# 🛠️ Technology Stack

| Technology | Purpose                    |
| ---------- | -------------------------- |
| Python     | Core Programming Language  |
| OpenCV     | Video Processing & Drawing |
| MediaPipe  | Hand Detection & Tracking  |
| NumPy      | Numerical Operations       |
| Webcam     | Real-Time Input Source     |

---

# 🧠 How It Works

### Step 1 — Capture Video

The webcam continuously captures live video frames.

### Step 2 — Detect Hand Landmarks

MediaPipe identifies 21 hand landmarks in real time.

### Step 3 — Analyze Finger Positions

The application determines which fingers are raised.

### Step 4 — Recognize Gestures

Different gestures trigger different actions:

* ☝️ Index Finger → Drawing Mode
* ✌️ Index + Middle Finger → Selection Mode

### Step 5 — Render Drawing

The detected finger movements are drawn on a virtual canvas and displayed live.

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Air-Drawing.git
cd Air-Drawing
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Application

Launch the application:

```bash
python main.py
```

Press:

```text
Q
```

to exit the application.

---

# 🎮 Controls

| Gesture                  | Action          |
| ------------------------ | --------------- |
| ☝️ Index Finger          | Draw            |
| ✌️ Index + Middle Finger | Selection Mode  |
| 🧽 Eraser Tool           | Remove Drawings |
| 🗑️ Clear Canvas         | Reset Canvas    |

---

# 💡 Applications

### 🎓 Virtual Teaching Boards

Create touchless whiteboard systems for online education.

### 🤖 Gesture-Based Interfaces

Develop interactive gesture-controlled applications.

### 🖥️ Human-Computer Interaction

Explore natural interaction methods without physical devices.

### 🎨 Creative Digital Art

Enable hands-free drawing experiences.

### 📚 Computer Vision Learning

Understand real-world applications of hand tracking technology.

---

# 📊 Skills Demonstrated

This project showcases:

* Computer Vision
* OpenCV
* MediaPipe
* Hand Tracking
* Gesture Recognition
* Real-Time Video Processing
* Human-Computer Interaction
* Python Development

---

# 🔮 Future Enhancements

### 💾 Save Drawings

Export drawings as image files.

### ↩️ Undo / Redo

Support editing history.

### 🎯 Advanced Gesture Controls

Add shortcuts for drawing actions.

### 🎨 Enhanced User Interface

Improve visual design and usability.

### 📱 Mobile Integration

Support mobile and tablet devices.

### ☁️ Cloud Storage

Save artwork online.

---

# 🎓 Learning Outcomes

Through this project, learners can understand:

* Computer Vision Fundamentals
* Hand Tracking Systems
* Gesture Recognition Techniques
* OpenCV Applications
* Real-Time Image Processing
* Human-Computer Interaction

---

# ⚠️ Disclaimer

This project is developed for educational and learning purposes.

Performance may vary depending on lighting conditions, camera quality, and hand visibility.

---

# 👩‍💻 Developer

## Rimpa Das

B.Tech Computer Science & Engineering
Brainware University

Passionate about Artificial Intelligence, Computer Vision, and developing innovative gesture-based applications.

### Technical Skills Demonstrated

* Python
* OpenCV
* MediaPipe
* Computer Vision
* Hand Tracking
* Gesture Recognition
* Image Processing

---

*"Transforming human gestures into interactive digital experiences through Computer Vision."*

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

🚀 Share it with others

---

<div align="center">

# 🎨 Air Drawing – Virtual Painter

### Draw Without Touching. Create Without Limits.

**Computer Vision • OpenCV • MediaPipe • Hand Tracking**

Built with ❤️ by Rimpa Das

</div>
