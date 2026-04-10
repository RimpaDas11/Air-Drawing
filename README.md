# 🎨 Air Drawing – Virtual Painter using Hand Tracking

A real-time **gesture-based drawing application** that enables users to draw in the air using hand movements captured via a webcam. Built using **Computer Vision** with **OpenCV** and **MediaPipe**, this project eliminates the need for traditional input devices like a mouse or stylus.

---

## 🚀 Features

- ✋ Real-time hand detection and tracking  
- 👆 Draw using index finger gestures  
- ✌️ Selection mode using multiple fingers  
- 🌈 Multiple color options  
- 🧽 Eraser tool for corrections  
- 🗑️ Clear canvas functionality  
- 📷 Fully webcam-based interaction  
- ⚡ Smooth and responsive drawing experience  

---

## 🛠️ Technologies Used

- **Python** – Core programming language  
- **OpenCV** – Image processing and video capture  
- **MediaPipe** – Hand tracking and landmark detection  
- **NumPy** – Numerical operations  

---

## 📂 Project Structure

```

Air-Drawing/
│── main.py              # Main application file
│── handTracker.py      # Hand tracking module
│── requirements.txt    # Dependencies
│── images/             # UI assets
│── README.md           # Documentation

````

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Air-Drawing.git
cd Air-Drawing
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
python main.py
```

👉 Press **Q** to exit the application.

---

## 🧠 How It Works

* The webcam captures real-time video input
* MediaPipe detects hand landmarks (21 key points)
* Finger positions are analyzed
* Different gestures trigger different actions:

  * ☝️ Index finger → Drawing mode
  * ✌️ Index + middle finger → Selection mode
* Drawing is rendered on a virtual canvas and merged with live video

---

## 📸 Output

* Interactive webcam window
* Draw in air using finger movements
* Select colors from the top panel
* Erase or clear the drawing easily

---

## 💡 Applications

* Virtual whiteboard for teaching
* Touchless UI systems
* Gesture-controlled interfaces
* Computer vision learning projects

---

## 📌 Future Enhancements

* 💾 Save drawings as images
* ↩️ Undo / Redo functionality
* 🎯 Gesture-based shortcuts
* 🎨 Improved UI/UX design
* 📱 Integration with mobile/web apps

---
