# 🦖 GestureDino: Play with Your Hands 🖐️

A computer vision-based Dino game where you control the character using **hand gestures** captured through your webcam.

---

## 🚀 Overview

GestureDino replaces traditional keyboard controls with **real-time hand gesture recognition**.

Using your webcam, the system detects your hand movements and translates them into game actions.

👉 No keyboard. Just your hand.

---

## 🎮 Features

* 🖐️ Gesture-based controls
* 🎥 Real-time webcam tracking
* ⚡ Lightweight and fast execution
* 🤖 Built using Computer Vision
* 🎯 Simple and beginner-friendly project

---

## 🕹️ Controls

Control the Dino using your hand:

* ✊ **Hand Close (Fist)** → Jump
* ✋ **Hand Open** → Run

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe

---

## 📂 Project Structure

```
gesture-dino/
│── __pycache__/        # Compiled Python files (auto-generated)
│── directkeys.py       # Handles keyboard input simulation
│── handmarks.py        # Detects hand landmarks using MediaPipe
│── main.py             # Main program (gesture detection + game control)
```

---

## ⚙️ How It Works

1. Webcam captures your hand
2. `handmarks.py` detects hand landmarks
3. Gesture logic identifies:

   * Open hand
   * Closed fist
4. `directkeys.py` simulates key presses
5. Dino game responds accordingly

---

## ▶️ How to Run

### 1. Clone the Repository

```bash id="c1"
git clone https://github.com/your-username/gesture-dino.git
cd gesture-dino
```

### 2. Install Dependencies

```bash id="c2"
pip install opencv-python mediapipe
```

### 3. Run the Project

```bash id="c3"
python main.py
```

---

## ⚠️ Requirements

* Webcam access
* Python 3.x installed
* Good lighting for accurate gesture detection

---

## 💡 Future Improvements

* 🎯 Add more gestures (duck, pause)
* 📱 Mobile/Web version
* 🧠 Improve accuracy with advanced models
* 🎮 Add scoring UI or overlay

---

## 🤝 Contributing

Feel free to fork this repo and improve it. Pull requests are welcome!

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🌟 Support

If you like this project, give it a ⭐ on GitHub!
