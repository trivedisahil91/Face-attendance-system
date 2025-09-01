# Face based attendance system using python and openCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/) 

---
## 📌 Overview
A Python-based **Face Recognition Attendance System** built using **OpenCV** and **Haar cascades**, designed to automatically detect and mark attendance in real time via webcam feed.
---

### What steps you have to follow??
- Download or clone my Repository to your device
- type `pip install -r requirements.txt` in command prompt(this will install required package for project)
- Create a `TrainingImage` folder in a project folder.
- open `attendance.py` and `automaticAttendance.py`, change all the path accoriding to your system
- Run `attandance.py` file

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named `TrainingImage`. more you give the image to system, the better it will perform while recognising the face.
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- It will take some time(depends on you system).
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.



---

## 🚀 Features
- Real-time face detection and recognition  
- Attendance logging with timestamp (Name, Date, Time)  
- Save logs in **CSV or Excel** formats  
- Lightweight and easy to use  

---

## 🛠️ Tech Stack
- **Python 3**  
- **OpenCV**  
- **NumPy**  
- **Pandas**  

---

## 📂 Project Structure
```

Face-Attendance-System/
│-- dataset/               # Captured face images
│-- trainer/               # Trained model files
│-- Attendance.csv         # Attendance log file
│-- takeImage.py           # Capture face images
│-- trainImage.py          # Train recognition model
│-- attendance.py          # Run attendance system
│-- requirements.txt       # Dependencies
│-- README.md              # Documentation

````

---

## 📥 Installation & Download

1. **Clone the repository**
   ```bash
   git clone https://github.com/trivedisahil91/Face-attendance-system.git
````

2. **Navigate to the project folder**
   ```bash
   cd Face-attendance-system
````

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
````

4. **Run the scripts**

   * Capture face images:

     ```bash
     python takeImage.py
````
   * Train the model:

     ```bash
     python trainImage.py
````
   * Mark attendance:

     ```bash
     python attendance.py
````

---

## 📊 Sample Output

| Name  | Date       | Time     |
| ----- | ---------- | -------- |
| Sahil | 2025-09-02 | 10:15:23 |
| Ravi  | 2025-09-02 | 10:16:45 |

---

## 🤝 Author

👤 **Sahil Trivedi**

* GitHub: [@trivedisahil91](https://github.com/trivedisahil91)
* LinkedIn: [Sahil Trivedi](https://linkedin.com/in/your-profile)

---

## 📜 License

This project is licensed under the **MIT License**.

```
---
