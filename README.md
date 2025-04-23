# Virtual-Mouse-Using-Hand-Gestures
# 🖱️ Virtual Mouse using Hand Gestures

This is a **Virtual Mouse** project that uses a webcam and hand gesture recognition to control mouse actions such as cursor movement, left-click, right-click, double-click, and screenshot—all without touching your physical mouse!



## 🛠️ Features

- Move mouse cursor using your **index finger**
- Perform **left click** with a specific gesture
- Perform **right click** with another gesture
- Perform **double click** and **take a screenshot**
- Uses **MediaPipe** for hand detection and tracking
- Real-time gesture detection using **OpenCV**

## 🧠 How it Works

The project uses:
- **MediaPipe** to detect hand landmarks
- Calculates angles and distances between fingers using a custom `util.py` module
- Maps gestures to mouse actions:
  - 🟢 **Index finger moved**: Moves mouse cursor
  - 🟢 **Left click**: Gesture involving index and middle finger
  - 🟢 **Right click**: Gesture with specific angles
  - 🟢 **Double click**: Both fingers folded gesture
  - 🟢 **Screenshot**: Close thumb and index tip

## 🧰 Technologies Used

- [Python 3](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [MediaPipe](https://developers.google.com/mediapipe)
- [pyautogui](https://pypi.org/project/pyautogui/)
- [pynput](https://pypi.org/project/pynput/)


**🙋‍♀️ 👩‍💻 Developed by**

**Anushka Gupta
B.Tech IT, PSIT Kanpur**
