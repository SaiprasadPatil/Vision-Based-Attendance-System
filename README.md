# Vision-Based Attendance System 🎯

A Flask-based web application that uses **OpenCV** and **face recognition** to automate the attendance process. This system captures images from a webcam, identifies registered users using machine learning, and marks their attendance in a CSV file.

## 📸 Features

- 🧠 Face detection using Haar Cascade
- 🤖 Face recognition using K-Nearest Neighbors (KNN)
- 📁 Automatic attendance logging into a dated CSV file
- 🔒 Unique identification using `Name_RollNumber`
- 📅 Daily attendance records
- 🧑‍💻 Add new users with face capture and model retraining
- 🖼️ Custom UI using `background.png`

---

## 🔧 Tech Stack

- Python
- OpenCV
- Flask
- NumPy, Pandas
- scikit-learn
- HTML (Jinja2 Templates)
- Joblib (for model persistence)

---

## 🚀 Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/vision-attendance-system.git
   cd vision-attendance-system
## ⚙️ Installation & Running the App

1. **Install dependencies**  
   Make sure you have Python installed. Then run:

   ```bash
   pip install -r requirements.txt
Attendance/
static/
static/faces/
background.png   <-- place this in the project root directory
python app.py
http://127.0.0.1:5000/

