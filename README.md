<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,50:764ba2,100:f093fb&height=200&section=header&text=👤%20FACE%20RECOGNITION%20ATTENDANCE&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Intelligent%20Attendance%20System%20with%20Facial%20Recognition&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

<p>
  <img src="https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=for-the-badge&logo=statuspage&logoColor=white"/>
  <img src="https://img.shields.io/badge/Version-2.0.0-blue?style=for-the-badge&logo=semver&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=opensourceinitiative&logoColor=white"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-ff69b4?style=for-the-badge&logo=github&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tkinter-FFD700?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-FF6B6B?style=for-the-badge&logo=tensorflow&logoColor=white"/>
</p>

<br/>

> ### *"One Face. One Record. Zero Proxy."*
> Face Recognition Based Attendance System automates attendance tracking using advanced facial recognition, eliminating manual entry and preventing proxy attendance in real-time.

<br/>

<a href="#-features">✨ Features</a> · <a href="#-tech-stack">🛠 Tech Stack</a> · <a href="#-getting-started">🚀 Get Started</a> · <a href="#-contributing">🤝 Contribute</a>

<br/>

</div>

---

## 🎯 Project Objective

**Face Recognition Attendance System** is a smart, GUI-driven attendance management solution designed for:

- 🏫 **Educational Institutions** — Schools, colleges, and universities seeking automated attendance
- 🏢 **Corporate Offices** — Companies tracking employee presence without manual processes
- 📚 **Training Centers** — Organizations needing efficient batch-wise attendance records
- 🎓 **Exam Halls** — Reducing time spent on roll calls, increasing exam duration

It doesn't just log names — it *recognizes*, *verifies*, and *records* with absolute accuracy.

---

## ✨ Features

<details>
<summary><b>👤 1. Advanced Facial Recognition Engine</b></summary>

<br/>

- **LBPH Algorithm** — Local Binary Patterns Histograms for lightning-fast face matching
- **Real-Time Detection** — Processes 30+ fps video stream without lag
- **Multi-Face Support** — Recognizes multiple students simultaneously in crowded environments
- **Unknown Face Handling** — Flags and logs unregistered faces with audio-visual alerts
- **Lighting Adaptive** — Works reliably under varying lighting conditions

</details>

<details>
<summary><b>🔐 2. Secure Student Registration</b></summary>

<br/>

- **Password-Protected Enrollment** — Only authorized personnel can register new students
- **Automated Face Capture** — Collects 100+ facial samples from different angles
- **Duplicate Detection** — Prevents duplicate entries for the same student
- **Roll Number Validation** — Integrates with existing student databases
- **Batch Import/Export** — Bulk register students from CSV files

</details>

<details>
<summary><b>📊 3. Intelligent Attendance Tracking</b></summary>

<br/>

- **Auto Daily Logs** — Creates new attendance CSV every morning automatically
- **Timestamp Recording** — Captures precise entry time down to the second
- **One-Entry-Per-Day** — Prevents duplicate attendance for the same student
- **Real-Time Display** — Live table showing today's attendance on the main screen
- **Absence Reports** — Auto-generates absence lists for follow-up actions

</details>

<details>
<summary><b>📈 4. Comprehensive Analytics Dashboard</b></summary>

<br/>

After attendance sessions, view:

| Metric | What It Tracks |
|--------|----------------|
| 📅 Daily Attendance % | Overall attendance rate for the day |
| 📋 Student-wise Report | Individual attendance history |
| 📉 Absence Trends | Students with chronic absenteeism |
| ⏰ Entry Times | Average entry time, latecomers flagging |
| 👁️ Recognition Accuracy | System confidence scores per face match |

</details>

<details>
<summary><b>🎚️ 5. Flexible Configuration & Customization</b></summary>

<br/>

- **Adjustable Confidence Threshold** — Fine-tune recognition sensitivity
- **Custom Attendance Rules** — Set time windows, grace periods, late marking
- **Multi-Class Support** — Manage different batches/departments separately
- **Export Formats** — CSV, Excel, PDF report generation
- **Backup & Recovery** — Auto-backup attendance data to prevent data loss

</details>

---

## 🛠️ Tech Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **GUI Framework** | Tkinter | Cross-platform user interface |
| **Computer Vision** | OpenCV + OpenCV-Contrib | Face detection & recognition |
| **ML Algorithm** | LBPH Face Recognizer | Facial pattern matching |
| **Data Processing** | Pandas, NumPy | Attendance records & analytics |
| **Image Processing** | Pillow (PIL) | Photo manipulation & storage |
| **Data Storage** | CSV Files | Lightweight, portable records |
| **Language** | Python 3.7+ | Fast, readable, maintainable code |

## 🏗️ System Architecture
