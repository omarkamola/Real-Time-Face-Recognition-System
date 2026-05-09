# Real-Time Face Recognition System

### Pipeline:
Face Detection (HOG) → Face Encoding (dlib) → Face Matching → Real-Time Recognition

---

## Project Overview

This project performs real-time face recognition using a webcam.

The system:
- Detects faces in video frames
- Extracts facial encodings
- Compares detected faces with stored encodings
- Displays the recognized person's name in real time

The project uses:
- OpenCV for video processing
- face_recognition / dlib for face detection and recognition
- Pickle for local database storage

---

## Notebook Workflow

1. **Cell 1** → Install required libraries  
2. **Cell 2** → Create project structure and database  
3. **Cell 3** → Register multiple people  
4. **Cell 4** → Run real-time face recognition  
5. **Cell 5** → Delete a person from the database  
6. **Cell 6** → Display database contents
