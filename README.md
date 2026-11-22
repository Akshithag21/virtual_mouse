# 🖱️ Virtual Mouse Using Hand Gestures

## 📌 Project Overview

The **Virtual Mouse Using Hand Gestures** is a computer vision-based project that allows users to control their computer mouse using simple hand movements in front of a webcam.

Instead of using a physical mouse, this project uses hand tracking technology to detect finger movements and perform mouse operations such as cursor movement, clicking, and scrolling.

It is developed using Python and libraries like OpenCV, MediaPipe, and PyAutoGUI.

## 🎯 Objectives

- To develop a touch-free mouse control system.
- To detect and track hand movements in real time.
- To control the mouse cursor using the index finger.
- To perform clicking and scrolling using finger gestures.

## 🛠️ Technologies Used

| Technology | Purpose                                         |
| ---------- | ----------------------------------------------- |
| Python     | Main programming language                       |
| OpenCV     | Captures and processes webcam video             |
| MediaPipe  | Detects and tracks hand landmarks               |
| PyAutoGUI  | Controls mouse movements, clicks, and scrolling |

## ✨ Features

- **Cursor Movement:** Move the index finger to control the mouse pointer.
- **Mouse Clicking:** Bring the thumb and index finger close together to perform a click.
- **Scrolling:** Use the relative positions of the index and middle fingers to scroll up and down.
- **Real-Time Hand Tracking:** Detects hand landmarks through the webcam.
- **Touch-Free Interaction:** Control basic mouse operations without a physical mouse.

## ⚙️ How It Works

1. The webcam captures real-time video.
2. OpenCV processes the video frames.
3. MediaPipe detects the hand and identifies 21 hand landmarks.
4. The index finger position is used to move the mouse cursor.
5. When the thumb and index finger come close vertically, a mouse click is triggered.
6. The relative vertical distance between the index and middle fingers controls scrolling.

## 📂 Project Structure

```text
Virtual-Mouse/
│
├── main.py          # Main Python implementation
├── README.md        # Project documentation
└── requirements.txt # Required Python libraries
```

## 🚀 Installation and Setup

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/Virtual-Mouse.git
```

**Step 2: Navigate to the project folder**

```bash
cd Virtual-Mouse
```

**Step 3: Install the required libraries**

```bash
pip install opencv-python mediapipe pyautogui
```

**Step 4: Run the project**

```bash
python main.py
```

Make sure your webcam is connected and accessible before running the application.

## 💻 Requirements

- Python 3.x
- Working webcam
- Computer or laptop
- Internet connection for installing dependencies

## 🌍 Applications

- Touch-free computer interaction.
- Human-computer interaction systems.
- Basic accessibility solutions.
- Gesture-controlled interfaces.
- Computer vision learning and experimentation.

## 🔮 Future Enhancements

- Add separate left-click and right-click gestures.
- Implement drag-and-drop functionality.
- Improve cursor accuracy and movement smoothness.
- Add volume control using hand gestures.
- Develop a graphical user interface (GUI).

## 👨‍💻 Author

Naga Akshitha Gunuguntla

GitHub: [Akshithag21](https://github.com/Akshithag21)

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with Python, OpenCV, MediaPipe and PyAutoGUI.**
