
# **AI-Powered Face Recognition Attendance System**

This project is an **AI-powered face recognition attendance system** designed to automate the process of attendance tracking using computer vision and machine learning techniques. The system employs Python, **OpenCV**, and **Pandas** for real-time face detection and attendance marking, achieving **94.5% accuracy**.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Performance](#performance)
- [Contributions](#contributions)
- [License](#license)

## Overview

This **Face Recognition Attendance System** automates the manual attendance process using face recognition technology. The system utilizes a **CSV file** for attendance tracking, allowing for efficient integration and management of attendance data. It automatically detects and records faces from webcam footage, marking attendance accordingly.

### Key Features:
- **Face Recognition**: Identifies faces using deep learning models for accurate attendance tracking.
- **Automated Attendance**: Eliminates manual attendance marking by recognizing faces in real-time.
- **CSV-Based Tracking**: Extracts data from a **CSV file**, enabling seamless integration and management of attendance records.
- **High Accuracy**: Achieves **94.5% accuracy** in face recognition.

## Key Features

- **Real-Time Face Detection**: Detects and recognizes faces in live video feeds.
- **Automated CSV Tracking**: Marks attendance in a CSV file, saving data in real-time.
- **Seamless Data Extraction**: Extracts information from the CSV file to handle diverse datasets and maintain records.
- **Attendance Log**: Tracks students or employees’ attendance automatically, reducing human error and time spent on manual entry.

## Technologies Used

- **Python**: The primary language used for face recognition and automation.
- **OpenCV**: For real-time video feed capture, face detection, and processing.
- **Pandas**: For handling and manipulating attendance data stored in CSV format.
- **Face Recognition Libraries**: Used to detect and recognize faces from video footage.

## How It Works

1. **Face Recognition**:
   - The system utilizes the webcam to capture real-time footage of individuals.
   - The **OpenCV** library is used to process each frame of the video and detect faces.
   - **Face recognition models** match detected faces to known individuals stored in the system.

2. **Automated Attendance Marking**:
   - Upon successful recognition, the system automatically updates the attendance CSV file.
   - Each recognized face is marked with the corresponding timestamp, allowing for accurate tracking of attendance.

3. **Data Extraction**:
   - The system can extract data from CSV files to handle diverse datasets, providing flexibility to support different formats or structures.
   - **Pandas** is used to manipulate and organize the attendance records for further analysis or reporting.

## Installation

To set up the **AI-powered Face Recognition Attendance System** on your machine, follow these steps:

### Prerequisites

- Python 3.x
- Required Python libraries: `opencv-python`, `face_recognition`, `pandas`, `numpy`

### Steps to Install:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/AI-Face-Recognition-Attendance.git
   cd AI-Face-Recognition-Attendance
   ```

2. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Make sure you have a webcam connected to your machine for real-time face detection.

4. Place the **CSV file** that will track attendance in the same directory, or specify its path in the script.

## Usage

1. To run the system, use the following command:

   ```bash
   python face_recognition_attendance.py
   ```

2. The program will start the webcam and begin detecting faces in real-time.
3. When a recognized face is detected, it will mark the attendance and store it in the **CSV file**.

### Example Output:

Upon detecting a face, the system will update the CSV file with the following structure:

| Name     | Date       | Time    | Status   |
|----------|------------|---------|----------|
| Sanuth   | 2025-04-14 | 10:15 AM| Present  |
| RajSekar | 2025-04-14 | 10:16 AM| Present  |

## Performance

- **Accuracy**: The system achieves **94.5%** accuracy in recognizing faces, ensuring reliable attendance tracking.
- **Real-Time Processing**: The system operates in real-time, detecting faces and updating attendance within seconds.

## Contributions

Feel free to contribute to this project by:
1. Forking the repository.
2. Creating a new branch for your feature or fix.
3. Committing your changes.
4. Submitting a pull request.

## License

This project is licensed under the MIT License.

---

