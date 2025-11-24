# Face Recognition Attendance System

This repository contains a simple face recognition based attendance system implemented in Python.

Contents
- `main.py` - main application file
- `face_recognition.py` - face detection/recognition helpers
- `train.py` - code to train face recognizer
- `Student.py` - student model
- `haarcascade_frontalface_default.xml` - Haar cascade for face detection
- `college_images/` - folder containing images used for training
- `data/` - (optional) runtime data / generated files

Requirements
- Python 3.8+
- See `requirements.txt` for common dependencies.

Quick start
1. (Optional) create a virtual environment:

   python -m venv venv
   .\venv\Scripts\Activate.ps1

2. Install dependencies:

   pip install -r requirements.txt

3. Train the recognizer (if needed):

   python train.py

4. Run the main app:

   python main.py

Notes
- The project uses OpenCV for face detection and recognition. Depending on your OS, installing OpenCV may require build tools.
- The repository currently includes image folders; if those contain many large files you may prefer to add them to Git LFS or remove from repo.

