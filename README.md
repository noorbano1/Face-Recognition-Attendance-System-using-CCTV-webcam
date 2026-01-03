# Automated Facial Recognition Attendance System Using CCTV

## 📌 Project Overview

This project is a **real-time Automated Facial Recognition Attendance System** that uses **CCTV/Webcam feeds** to automatically detect and recognize faces and mark attendance without manual intervention. The system is designed mainly for **educational institutions** but can be extended to **employee attendance** as well.

The goal is to reduce proxy attendance, save time, and provide accurate, automated attendance records.

---

## 🎯 Objectives

* Automate attendance marking using facial recognition
* Work with **real-time CCTV/Webcam video streams**
* Maintain daily attendance records
* Reduce manual effort and human errors
* Provide a scalable solution for universities and offices

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Computer Vision:** OpenCV
* **Face Recognition:** Haar Cascade / LBPH / Deep Learning models
* **GUI:** Tkinter
* **Database:** CSV / MySQL / SQLite (configurable)
* **Framework (Optional):** Django (for web-based interface)

---

## ⚙️ System Modules

### 1️⃣ Face Detection & Recognition Module

* Captures video from CCTV or webcam
* Detects human faces in real time
* Recognizes registered faces using trained models

### 2️⃣ Student Registration Module

* Captures multiple face images per student
* Stores data with unique student ID
* Automatically trains the facial recognition model

### 3️⃣ Attendance Marking Module

* Marks attendance automatically on face recognition
* Prevents duplicate entries on the same day
* Stores date and time with attendance

### 4️⃣ Reporting Module

* Generates daily attendance reports
* Supports CSV and database records
* Can be extended for monthly summaries

---

## 🔄 System Workflow

1. Camera/CCTV captures live video
2. Faces are detected from video frames
3. Detected faces are matched with trained data
4. If match found → attendance marked
5. Attendance stored in database/report

---

## 🖥️ Installation & Setup

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/facial-attendance-system.git
```

### Step 2: Install Required Libraries

```bash
pip install opencv-python
pip install numpy
pip install pillow
pip install tkinter
```

### Step 3: Run the Project

```bash
python main.py
```

---

## 📂 Project Structure

```
project-folder/
│── dataset/
│── trainer/
│── attendance/
│── haarcascade_frontalface_default.xml
│── main.py
│── train.py
│── README.md
```

---

## ✅ Features

* Real-time face detection
* Automatic attendance marking
* Duplicate attendance prevention
* Simple and user-friendly interface
* Extendable for salary calculation and analytics

---

## 🚀 Future Enhancements

* Web-based dashboard using Django
* Employee salary calculation module
* Cloud database integration
* Mask & hijab-aware face recognition
* Mobile app integration

---

## 👩‍🎓 Developed By

**Noorbano**
Final Year BS Computer Science Student
Project Title: *Automated Facial Recognition Attendance System Using CCTV*

---

## 📜 License

This project is developed for **educational purposes** and can be modified or extended with proper attribution.

---

## 📞 Contact

For queries or collaboration, feel free to connect.
