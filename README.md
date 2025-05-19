# 🚗 Authorized Vehicle Number Plate Recognition (VNPR) System

## 📘 Introduction

The Authorized Vehicle Number Plate Recognition (VNPR) System is a real-time application that detects vehicles and extracts their number plates from live camera footage using deep learning. It processes video frames, identifies vehicles and their number plates using YOLOv8, applies Optical Character Recognition (OCR) to extract text, and verifies the number against a pre-defined database to allow or deny access. This project aims to automate entry management systems such as parking lots, institutional gates, or residential communities.

---

## 🧰 Tech Stack

| Component                  | Technology Used                  |
|---------------------------|----------------------------------|
| **Programming Language**  | Python 3.10+                      |
| **Object Detection**      | YOLOv8 (Ultralytics)             |
| **OCR Engine**            | EasyOCR / Tesseract              |
| **Database**              | SQLite (or any other lightweight DB) |
| **Frameworks/Libraries**  | OpenCV, NumPy, Ultralytics YOLO, EasyOCR |
| **IDE/Tool**              | VS Code / Jupyter Notebook       |

---

## 🏗️ Architecture & Flow Diagram

### 🔄 System Workflow

1. **Video Input** – Live camera feed or sample video
2. **Frame Extraction** – Extracts frames at regular intervals
3. **Vehicle Detection** – YOLOv8 detects vehicles in the frame
4. **Number Plate Detection** – YOLOv8 detects license plate
5. **OCR Processing** – Text is extracted from the plate
6. **Database Verification** – Text is checked against an authorized list
7. **Access Decision** – Allow or deny access based on match

### 📊 Architecture Flow Diagram
![System Architecture](images/how-to-make-a-research-poster.png)
