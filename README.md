# Fingers_to_binary
A real-time computer vision system that detects the number you're showing with your hand—interpreting it directly in **binary** using MediaPipe and OpenCV.

<h1 align="center">
  <img src="https://media.giphy.com/media/glJdAXojfP3wPEg84a/giphy.gif" alt="Binary Countdown GIF">
</h1>

---

## Binary Gesture Recognition via Hand Tracking

This project is a lightweight but powerful computer vision application that recognizes hand gestures and translates them into **binary numbers**, based on which fingers are extended. The system uses real-time webcam input and processes the hand pose using **Google's MediaPipe**, mapping each finger to its corresponding binary value (from `2⁰` to `2⁴`).

The system is designed for educational purposes, human-computer interaction experiments, or just for fun—see how many numbers you can count in binary using only one hand!

### Features

- 🖐️ **Real-time hand tracking** using MediaPipe
- 🔢 **Binary number detection** based on finger positions
- 📷 **Live webcam input** with OpenCV
- 💻 **Lightweight and fast**, no GPU required
- 🎯 Accurate finger state detection (up/down)

### Tools & Frameworks

- [MediaPipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)
- Python 3.8+

### Binary Mapping

| Finger (Left Hand) | Binary Value |
|---------------------|--------------|
| Thumb               | 2⁰ (1)        |
| Index               | 2¹ (2)        |
| Middle              | 2² (4)        |
| Ring                | 2³ (8)        |
| Pinky               | 2⁴ (16)       |

| Finger (Right Hand)  | Binary Value |
|---------------------|--------------|
| Thumb               | 2⁵ (32)       |
| Index               | 2⁶ (64)       |
| Middle              | 2⁷ (128)      |
| Ring                | 2⁸ (256)      |
| Pinky               | 2⁹ (512)      |

Example: If your index and pinky fingers are up, the number shown is `2 + 16 = 18`.

---

## Project Structure

📁 `fingers_to_binary.ipynb` — Main script for hand tracking and binary interpretation  
📁 `README.md` — This file :)

---

## How to Run

1. Clone this repo:
```bash
git clone https://github.com/Mxz-11/Fingers_to_binary.git
cd Hand2Binary
```
