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

## Project Structure

```text
project/
│
├── database/
│   ├── Omar/
│   └── Ahmed/
│
├── encodings.pkl
└── notebook.ipynb
```

---

## Notebook Workflow

1. **Cell 1** → Install required libraries
2. **Cell 2** → Create project structure and database
3. **Cell 3** → Add a single person to the database
4. **Cell 4** → Add all team members at once
5. **Cell 5** → Run real-time face recognition
6. **Cell 6** → Delete a person from the database
7. **Cell 7** → Display database contents

---

## Cell 3 - Add a Single Person

Before running:

- Create a folder inside `database/`
- Name the folder after the person
- Add 2 to 5 clear photos inside the folder
- Update the `PERSON_NAME` variable

Example:

```text
database/Omar/photo1.jpg
```

---

## Cell 4 - Add All Team Members

Before running:

- Create one folder per person inside `database/`
- Add 2 to 5 clear photos for each person

Example:

```text
database/Omar/photo1.jpg
database/Ahmed/photo2.jpg
```

---

## Notes

- Use clear front-facing photos for better accuracy
- Supported image formats:
  - `.jpg`
  - `.jpeg`
  - `.png`
  - `.webp`
- Press `q` to close the camera window
