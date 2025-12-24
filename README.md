# 🚁 Gesture-Driven Drone Simulator ✋

Gesture-Driven Drone Simulator is a **computer vision–based interactive simulation** where a virtual drone is controlled entirely using **hand gestures captured via a webcam** — no keyboard, mouse, or controller required.

The project leverages **MediaPipe Hand Tracking** and **OpenCV** to detect finger positions in real time and translate them into smooth drone movements inside a **3D-style simulated environment** with a **HUD and radar visualization**.

---

## 🚀 Features

* 🎥 Real-time webcam-based interaction
* ✋ Hand gesture tracking using MediaPipe
* 🧠 Gesture stabilization to reduce noise and false positives
* 🚁 Gesture-based drone navigation (no physical controller)
* 🌐 3D-style perspective grid simulation
* 📡 Live radar widget with sweep animation
* 📊 Heads-Up Display (HUD) showing gesture & drone state
* ⚡ Fully offline & real-time performance
* 🎓 Beginner-friendly yet powerful computer vision logic

---

## 🧑‍✈️ Gesture Controls

| Gesture                  | Action        |
| ------------------------ | ------------- |
| ✊ Rock (Fist)            | Land          |
| ✋ Open Palm              | Hover         |
| ✌️ Index + Middle        | Move Forward  |
| ☝️ Index Only            | Move Backward |
| 🤟 Index + Middle + Ring | Move Left     |

---

## 🛠️ Tech Stack

* Python 3
* OpenCV
* MediaPipe
* NumPy

---

## 📂 Project Structure

```
gesture-driven-drone-simulator/
│
├── main.py                # Main application script
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/gesture-driven-drone-simulator.git
cd gesture-driven-drone-simulator
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available:

```bash
pip install opencv-python mediapipe numpy
```

---

## ▶️ Run the Simulator

```bash
python main.py
```

📷 Ensure your **webcam is connected**
❌ Press **q** to quit the application

---

## 🧠 How It Works

1. Captures live webcam frames using OpenCV
2. Detects hand landmarks with MediaPipe Hands
3. Analyzes finger positions to classify gestures
4. Smooths gestures using a frame-history buffer
5. Updates drone movement with world constraints
6. Renders a simulated environment featuring:

   * Perspective grid
   * Drone body & rotors
   * Radar visualization
   * Heads-Up Display (HUD)

---

## 🚀 Use Cases

* Computer Vision & AI demonstrations
* Gesture-based Human–Computer Interaction (HCI)
* UAV & drone navigation prototypes
* Hackathons and academic projects
* Touchless control systems

---

## 🧪 Tested On

* Windows 10 / 11
* Python 3.9+
* Laptop webcam

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to **fork this repository** and submit a **pull request**.

---

## 📌 Future Enhancements

* Altitude & rotation gestures
* Multi-drone simulation
* Physics-based drone dynamics
* VR/AR integration
* Real drone hardware mapping

---

⭐ If you like this project, don’t forget to **star the repository**!
