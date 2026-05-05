# 🚀 Automated MediaPipe & YOLO Environment Setup (Windows)

This repository provides an automated solution for configuring a Python development environment specifically tailored for **MediaPipe** and **YOLOv8** on Windows systems. Designed for students and developers, this script handles dependency management and environment isolation automatically.

---

## 🛠 Key Features

- **Automated Python Provisioning:** Detects existing Python installations. If Python is missing, it automatically fetches and installs Python 3.11.
- **Environment Isolation:** Utilizes `venv` (Virtual Environment) to create a dedicated workspace (`myenv`), preventing library conflicts.
- **Dependency Management:** Automatically installs and upgrades:
  - `mediapipe` (Advanced computer vision solutions)
  - `ultralytics` (YOLOv8 object detection framework)
  - `opencv-python` (Real-time image and video processing)

---

## 📦 Installation Guide

Follow these steps to set up your environment:

1. **Download the Script:**
   - Navigate to the [Releases](https://github.com/chrisfoong/vision-env-setup.git) section.
   - Download the `setup_env.bat` file and place it in your project directory.

2. **Execute Deployment:**
   - Double-click `setup_env.bat`.
   - **Note:** If prompted by Windows SmartScreen, click *More Info* > *Run anyway*.
   - If a User Account Control (UAC) prompt appears for Python installation, select **Yes**.

3. **Verification:**
   - The script will begin downloading and installing the necessary components. This process typically takes 2–5 minutes.
   - Once completed, the message **"Setup Complete!"** will be displayed. Press any key to exit.

---

## 🧑‍💻 Usage Instructions

After execution, a directory named `myenv` will be created. This contains your isolated Python interpreter and libraries.

### Running Your Scripts
To execute your Python script (e.g., `main.py`) using the local environment, use the following command in your terminal:
```powershell
.\myenv\Scripts\python.exe main.py
