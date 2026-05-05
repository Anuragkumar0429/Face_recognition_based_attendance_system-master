<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Face%20Recognition%20Attendance%20System&fontSize=36&fontColor=ffffff&fontAlignY=38&desc=Real-Time%20Face%20Detection%20%7C%20Auto%20Attendance%20%7C%20Email%20Alerts&descAlignY=58&descSize=17&animation=fadeIn" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Real-Time+Face+Detection+👁️;Automated+Attendance+Marking+✅;SMTP+Email+Alerts+for+Absentees+📧;Haar+Cascade+%2B+LBPH+Recognition;Tkinter+GUI+%7C+CSV+Records+%7C+Password+Protected)](https://git.io/typing-svg)

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SMTP](https://img.shields.io/badge/SMTP-Email_Alerts-red?style=for-the-badge&logo=gmail&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

## 📌 Overview
An **automated classroom attendance system** using real-time face recognition. Students are registered, model is trained using **LBPH + Haar Cascade**, and attendance is marked automatically. Unknown faces trigger a **sound alert** and absentees get **SMTP email notifications** — all via a Tkinter GUI.

---

## 🗂️ Project Structure

```
Face_Recognition_Attendance_System/
├── main.py                              # 🚀 Run this
├── haarcascade_frontalface_default.xml  # Face detection model
├── TrainingImage/                       # Captured face samples
├── StudentDetails/StudentDetails.csv    # Student records
├── Attendance/                          # Daily attendance CSVs
└── TrainingImageLabel/Trainner.yml      # Trained LBPH model
```

---

## ⚙️ How It Works

```
Register Student → Capture 100+ Images → Train LBPH Model
       ↓
Start Attendance → Webcam detects faces in real-time
       ↓
Face Recognized?  ✅ YES → Mark Present  |  ❌ NO → Sound Alert
       ↓
Session Ends → Absentees notified via Email (SMTP)
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Face Detection | Haar Cascade Classifier |
| Face Recognition | LBPH Algorithm |
| GUI | Tkinter + ttk |
| Data Handling | Pandas, CSV |
| Email Alerts | smtplib, MIME |
| Image Processing | OpenCV, Pillow, NumPy |

---

## ⚡ Quick Start

```bash
git clone https://github.com/AnuragKumar0429/Face_Recognition_Attendance_System.git
cd Face_Recognition_Attendance_System
pip install opencv-contrib-python numpy pandas pillow
python main.py
```

---

## ✅ Features
- ✓ Real-time face detection & LBPH recognition
- ✓ Auto-captures 100+ training images per student
- ✓ Attendance saved with date & timestamp to CSV
- ✓ SMTP email alerts for absentees
- ✓ Sound alert for unknown faces
- ✓ Password-protected admin panel
- ✓ Cross-platform (Windows / Linux / macOS)

---

## 🙏 Acknowledgements
- [OpenCV](https://opencv.org) — For the powerful computer vision library
- [Shields.io](https://shields.io) — For beautiful badges
- [Capsule Render](https://github.com/kyechan99/capsule-render) — For the animated banner
- [Haar Cascade](https://github.com/opencv/opencv/tree/master/data/haarcascades) — For the pre-trained face detection model

---

<div align="center">

**Anurag Kumar Upadhyay**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anurag-kumar-upadhyay-9a2105285/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnuragKumar0429)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akupadhaya01@gmail.com)

<br/>

**If this project helped you, please ⭐ star the repo — it means the world!**

Made with ❤️ by **[Anurag Kumar Upadhyay](https://github.com/AnuragKumar0429)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
