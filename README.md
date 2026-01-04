# 🎯 Face Recognition Attendance System with Emotion Detection

A real-time **Face Recognition Based Attendance System** built using **Python**, **OpenCV**, and **Machine Learning**.  
The system identifies individuals through a webcam, detects their facial emotions, and automatically records attendance in an **Excel file** with timestamp.

---

## 🚀 Project Overview

This project captures live video from a webcam, recognizes faces by comparing them with stored images, detects the dominant facial emotion, and marks attendance only once per person per session.

It is useful for:
- Colleges & Schools  
- Offices & Organizations  
- Smart Classroom / Office Automation  

---

## 🧠 Key Features

- Real-time face detection and recognition  
- Facial emotion detection (Happy, Sad, Angry, Neutral, etc.)  
- Automatic attendance marking  
- Attendance saved in Excel format  
- Multiple face detection in a single frame  
- Prevents duplicate attendance entries  

---

## 🛠️ Technologies Used

- Python  
- OpenCV  
- face_recognition  
- FER (Facial Emotion Recognition)  
- Pandas  
- NumPy  
- Datetime  

---

## 📁 Repository Structure

```
face-recognition-attendance-emotion/
│
├── images/ # Known face images (image name = person name)
├── attendance.xlsx # Generated attendance file
├── face_attendance.py # Main Python script
├── requirements.txt # Required Python libraries
├── README.md # Project documentation
```
---
## 📊 Sample Attendance Output

| Name   | Timestamp           | Emotion |
|--------|---------------------|---------|
| Himesh | 2026-01-04 10:32:15 | Happy   |

---

## ⚙️ How It Works

1. Loads known face images and generates face encodings  
2. Starts webcam for real-time face detection  
3. Compares detected faces with known face encodings  
4. Recognizes the person and detects facial emotion  
5. Marks attendance with timestamp and emotion  
6. Saves attendance data into an Excel file  

---

🌟 Future Enhancements

→ Daily attendance sheet generation

→ Database integration (MySQL / PostgreSQL)

→ Web dashboard using Flask or Streamlit

→ Email notifications

→ Cloud-based deployment



---

👨‍💻 Author

Himesh Tyagi
B.Tech in Computer Science
Data Analytics & Machine Learning Enthusiast
