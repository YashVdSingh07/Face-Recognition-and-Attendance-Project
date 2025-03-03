# Face-Recognition-and-Attendance-Project

## 📌 Overview
This project implements a **Facial Recognition-based Attendance System** using **OpenCV, face_recognition, and Python**. The system detects faces from a live webcam feed, matches them with stored images, and logs attendance in a CSV file.

## ✨ Features
- 🎯 Real-time face detection & recognition
- 📋 Automatic attendance logging
- 🔍 Uses deep learning-based face encodings
- 🖼️ Works with pre-stored images for recognition
- 📝 Saves attendance records in `Attendance.csv`

## 📂 Folder Structure
```
Facial Recognition & Attendance System
│── .venv/                  # Virtual environment
│── ImagesAttendance/       # Folder with reference images
│── Attendance.csv          # CSV file for attendance log
│── AttendanceProject.py    # Main script
```


## 🎥 How It Works
1. **Face Encoding:**
   - Loads stored images from `ImagesAttendance`
   - Generates face encodings
2. **Face Detection & Recognition:**
   - Captures video from the webcam
   - Compares detected faces with stored encodings
3. **Attendance Logging:**
   - If a match is found, logs the name & timestamp in `Attendance.csv`

## 🖼️ Sample Output
![Face Recognition Example](Project%20Screenshot.png)

## 🛠️ Technologies Used
- **Python**
- **OpenCV**
- **face_recognition** (Dlib-based)
- **NumPy**
- **CSV File Handling**

## ❗ Troubleshooting
- If **no faces are detected**, ensure:
  - Images are **clear & properly aligned**
  - Lighting conditions are **adequate**
  - Image resolution is **not too large**

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome! Feel free to contribute improvements.

## 📞 Contact
For questions or suggestions, contact:

📧 Email: [yashvardhan1803@gmail.com](mailto:yashvardhan1803@gmail.com)

GitHub: [YashVdSingh07](https://github.com/YashVdSingh07)
