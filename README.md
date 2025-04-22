# 🚨 Drowsiness Detection System

A real-time driver drowsiness detection system using OpenCV, Dlib, and TensorFlow/Keras.  
The system monitors **eye closure** and **yawning** using a webcam and raises an alert if drowsiness is detected.

---

## 📌 Features

- Detects **closed eyes** using a trained CNN model
- Detects **yawning** using **Dlib 68 facial landmarks**
- Calculates how long the eyes have been closed
- Combines both indicators to trigger a drowsiness alert
- Plays an alarm sound when the user is drowsy
- Real-time processing via webcam

---

## 🧠 Technologies Used

- `Python`
- `OpenCV`
- `Dlib`
- `TensorFlow / Keras`
- `NumPy`
- `Haar Cascades`
- `Playsound` (for alarm)

---
## Download Links
- Dataset Link: [Driver Drowsiness Dataset (DDD)](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)
- 68 face landmarks file link: https://github.com/GuoQuanhao/68_points/blob/master/shape_predictor_68_face_landmarks.dat 
