# 🎓 Face Recognition Attendance System

A real-time Face Recognition Attendance System developed using **Python**, **OpenCV**, and **face_recognition (dlib)**.

This project detects faces from a live webcam feed, recognizes registered users, and automatically records attendance into a CSV file.

---

## 📌 Features

- ✅ Real-time face detection
- ✅ Face recognition using face encodings
- ✅ Automatic attendance marking
- ✅ CSV-based attendance storage
- ✅ Easy to add new users
- ✅ Live webcam support
- ✅ Fast face matching

---

## 🛠️ Tech Stack

- Python 3.10
- OpenCV
- face_recognition
- dlib
- NumPy
- CSV
- Webcam

---

## 📂 Project Structure

```
Face-Recognition-Attendance-System/
│
├── Images_Attendance/
│   ├── RONALDO.jpg
│   ├── MODI.jpg
│
├── Attendance.csv
├── AttendanceProject.py
├── main.py
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/YourUsername/Face-Recognition-Attendance-System.git

cd Face-Recognition-Attendance-System
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate

Windows

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install opencv-python
pip install face-recognition
pip install numpy
```

---

## ▶️ Run Project

```bash
python AttendanceProject.py
```

---

## 📸 How It Works

1. Store known face images inside **Images_Attendance**
2. Start the webcam.
3. Detect faces in real time.
4. Compare detected faces with stored encodings.
5. If matched:
   - Display student name
   - Record attendance in Attendance.csv
6. Ignore duplicate attendance entries.

---

## 📄 Attendance Output

Example

```
Name,Time,Date
Mithilesh,10:35:12,28/07/2026
Rahul,10:36:02,28/07/2026
```

---

## 🚀 Future Improvements

- Database Integration (MySQL/MongoDB)
- GUI Interface
- Student Login Panel
- Admin Dashboard
- Multiple Camera Support
- Cloud Attendance Storage
- Anti-Spoofing Detection
- Face Mask Recognition

---

## 📚 Learning Outcomes

This project helped me understand:

- Computer Vision
- Face Detection
- Face Recognition
- Image Encoding
- OpenCV
- Python File Handling
- Real-Time Webcam Processing

---

## 📜 License

This project is created for educational purposes.

If you use or modify this project, please give proper credit to the original project and mention your own modifications.

---

## 👨‍💻 Author

**Mithilesh Yadav**

B.Tech CSE Student

GitHub: https://github.com/Mithilesh1262/FaceTrack-Attendance


## ⭐ Project Status

✔ Completed

Current Version : v1.0

Upcoming Version (v2)

- Database Integration
- Flask Web App
- Admin Panel
- Face Registration Module
- Email Attendance Report.
