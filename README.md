Gesture-Driven Drone Simulator

A real-time hand gesture–controlled drone simulator built using MediaPipe, OpenCV, and Python.
The system uses computer vision to detect hand gestures via a webcam and maps them to drone movements inside a 3D-style simulated environment with HUD and radar visualization.

✨ Features

🖐️ Real-time hand gesture recognition using MediaPipe

🚀 Gesture-based drone control

Rock → Land

Open Palm → Hover

Scissors → Move Forward

Index Finger → Move Backward

Three Fingers → Move Left

🎮 3D-style drone simulation

📡 Live radar widget with sweeping animation

🧠 Gesture smoothing to reduce noise and false detection

📊 On-screen HUD displaying gesture, drone state, and position

⚡ Runs fully offline using a webcam

🛠️ Tech Stack

Python 3

OpenCV

MediaPipe

NumPy

📂 Project Structure
.
├── main.py          # Main application file
├── README.md        # Project documentation

▶️ How It Works

Webcam captures live video feed.

MediaPipe detects hand landmarks.

Finger states are analyzed to classify gestures.

Gestures are stabilized using a frame history buffer.

Drone position is updated based on recognized gestures.

A simulated 3D environment renders:

Drone body & rotors

Perspective grid

Radar visualization

HUD text

🧑‍✈️ Gesture Controls
Gesture	Action
✊ Rock (Fist)	Land
✋ Open Palm	Hover
✌️ Index + Middle	Move Forward
☝️ Index Only	Move Backward
🤟 Index + Middle + Ring	Move Left
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/gesture-driven-drone-simulator.git
cd gesture-driven-drone-simulator

2️⃣ Install Dependencies
pip install opencv-python mediapipe numpy

3️⃣ Run the Project
python main.py


📷 Ensure your webcam is connected and accessible

🖥️ Controls

Show gestures in front of the webcam

Press q to quit the application

📸 Demo Preview

(Optional: Add screenshots or a GIF here for better presentation)

🚀 Use Cases

Computer Vision & AI demos

Gesture-based HCI systems

UAV/drone control research prototypes

Hackathons & academic projects

Assistive and touchless control interfaces

📌 Future Improvements

Add right & upward movement gestures

Integrate real drone (ROS / PX4 / DJI SDK)

Improve depth perception

Multi-hand gesture support

VR/AR visualization

🤝 Contributing

Contributions, ideas, and improvements are welcome!
Feel free to fork this repo and submit a pull request.
