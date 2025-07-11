

# ✋ Gesture-Based Multimedia & Browser Control

A real-time gesture recognition system using **MediaPipe** and **OpenCV** that enables hands-free control of multimedia features (like volume & brightness) and browser access — enhancing accessibility and convenience.

---

## 🎯 Aim

Develop a Python-based system that recognizes **hand gestures** via webcam to:

* 🔊 Control system **volume** (up, down, mute/unmute)
* 💡 Adjust screen **brightness**
* 🌐 Launch and switch **browser tabs**

---

## 🧠 Key Features

* ✅ **Real-time gesture tracking** using MediaPipe
* 📡 Hands-free control of multimedia and browser actions
* 🧩 Integrated visual feedback (e.g., “Volume Up”, “Brightness Down”)
* 🤖 Uses distance & finger landmarks to determine gesture intent

---

## 🛠️ Tech Stack

| Component     | Description                              |
| ------------- | ---------------------------------------- |
| 🐍 Python     | v3.6+                                    |
| 📸 OpenCV     | For webcam video processing              |
| ✋ MediaPipe   | For real-time hand landmark tracking     |
| 🎛️ PyAutoGUI | For controlling volume & keyboard inputs |
| 💻 SBC        | Screen Brightness Control package        |
| 🌍 Webbrowser | Launch default system browser            |

---

## 🧮 Algorithm Workflow

1. **Initialize Camera & Hand Detector**
2. **Track Landmark Points** on the hand
3. **Identify Gestures** (e.g., finger positions, distance between fingertips)
4. **Perform Actions**:

   * ✊ Swipe → Tab switch
   * ✋ All fingers up → Open browser
   * 👍 Fingers together → Adjust brightness
   * ✌️ Finger movement → Volume control
5. **Display Feedback** on screen using OpenCV

---

## 📷 Live Demo Snapshot



<img width="479" height="310" alt="image" src="https://github.com/user-attachments/assets/973d775b-ce29-480b-949b-cedb8f5ca9a4" />




---

## 🔮 Future Enhancements

* 📱 Mobile version for smartphone gesture control
* 🔐 Gesture-based authentication system
* 🎙️ Combine gesture and voice control
* 🖐️ Support for dual-hand gestures
* 🎮 Add gestures to launch media apps or games

---

## 📚 References

* [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)
* [OpenCV Docs](https://docs.opencv.org/4.x/)
* [PyAutoGUI Docs](https://pyautogui.readthedocs.io/en/latest/)
* [Screen Brightness Control](https://github.com/Crozzers/screen-brightness-control)

---

## ✅ Conclusion

This project successfully demonstrates an intuitive, hands-free interaction system that enhances user accessibility. By integrating **gesture recognition** with **system control APIs**, users can effortlessly manage core PC functions with a simple wave or swipe of their hand.

