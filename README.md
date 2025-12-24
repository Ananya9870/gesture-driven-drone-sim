# Gesture-Driven Drone Simulator 🚁✋

Gesture-Driven Drone Simulator is a **computer vision–based interactive simulation** where a virtual drone is controlled entirely using **hand gestures captured via a webcam** — no keyboard, mouse, or controller required.

The project leverages **MediaPipe Hand Tracking** and **OpenCV** to detect finger positions in real time and translate them into smooth drone movements inside a **3D-style simulated environment with HUD and radar visualization**.

---

## 🚀 Features

- 🎥 **Real-time webcam-based interaction**
- ✋ **Hand gesture tracking using MediaPipe**
- 🧠 **Gesture stabilization** to reduce noise and false positives
- 🚁 **Gesture-based drone navigation**
- 🌐 **3D-style perspective grid simulation**
- 📡 **Live radar widget with sweep animation**
- 📊 **HUD displaying gesture, drone state, and position**
- ⚡ **Fully offline & real-time performance**
- 🎓 **Beginner-friendly yet powerful computer vision logic**

---

## 🧑‍✈️ Gesture Controls

| Gesture | Action |
|-------|--------|
| ✊ Rock (Fist) | Land |
| ✋ Open Palm | Hover |
| ✌️ Index + Middle | Move Forward |
| ☝️ Index Only | Move Backward |
| 🤟 Index + Middle + Ring | Move Left |

---

## 🛠️ Tech Stack

- **Python 3**
- **OpenCV**
- **MediaPipe**
- **NumPy**

---

## 📂 Project Structure

```bash
gesture-driven-drone-simulator/
│
├── main.py                # Main application script
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/gesture-driven-drone-simulator.git
cd gesture-driven-drone-simulator

2️⃣ Install Dependencies
pip install -r requirements.txt


If you don’t have requirements.txt, install manually:

pip install opencv-python mediapipe numpy

▶️ Run the Simulator
python main.py


📷 Make sure your webcam is connected
❌ Press q to quit the application

🧠 How It Works

Captures live webcam frames using OpenCV

Detects hand landmarks with MediaPipe Hands

Analyzes finger positions to classify gestures

Smooths gestures using a frame-history buffer

Updates drone movement with world constraints

Renders a simulated 3D environment with:

Perspective grid

Drone body and rotors

Radar visualization

Heads-Up Display (HUD)

🚀 Use Cases

Computer Vision & AI demonstrations

Gesture-based Human–Computer Interaction (HCI)

UAV & drone navigation prototypes

Hackathons and academic projects

Touchless control systems

🧪 Tested On

Windows 10 / 11

Python 3.9+

Laptop webcam

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repository and submit a pull request.
