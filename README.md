# ✋ Hand Gesture Controlled Dino Game

## 📌 About the Project

Imagine you are working and suddenly your internet stops working due to a router issue. While waiting for it to get fixed, most people turn to Chrome’s offline Dino game to pass the time.

This project enhances that experience by allowing users to play the Dino game using **hand gestures instead of keyboard inputs**.

The system captures live video from a webcam, detects the hand region, and interprets gestures (open/closed fist) to control the game automatically.

---

## 🎯 Objective

To build a real-time computer vision system that enables **touchless interaction** by controlling a game using hand gestures.

---

## ⚙️ Working Principle

The system works in two main steps:

1. **Hand Detection & Segmentation**

   * Extracts the hand region from the video feed
   * Removes background noise for accurate detection

2. **Finger/ Gesture Recognition**

   * Detects whether the hand is open or closed
   * Maps gestures to actions:

     * ✊ Closed Fist → Press SPACE (Jump)
     * ✋ Open Hand → Release SPACE

---

## 🧠 Approach

* Capture video using webcam
* Preprocess frames (grayscale, thresholding, contour detection)
* Segment hand region
* Detect gesture based on shape/finger count
* Trigger keyboard action automatically

---

## 🛠️ Requirements

### 🐍 Python

* Python 2.7 or above

### 📷 OpenCV

* Used for image processing and video capture
* Version 2.x or 3.x

### 🔢 NumPy

* Used for array operations and numerical computations

---

## 🚀 Key Features

* Real-time gesture recognition
* Touchless gameplay experience
* Lightweight and efficient implementation
* Uses basic computer vision techniques (no heavy ML required)

---

## 📈 Future Improvements

* Add deep learning for more accurate gesture recognition
* Support multiple gestures (duck, pause, etc.)
* Improve robustness in different lighting conditions
* Extend to other games and applications

---

## 🎮 Use Case

* Hands-free gaming
* Human-computer interaction
* Accessibility applications

---

## 👩‍💻 Author

**Ishita Kadyan**
Master’s in Computer Science & Engineering
