
---

# **Smart Face Recognition Attendance System**

An **AI-powered attendance system** using **Python**, **OpenCV**, and **Pandas** that automates traditional attendance tracking through facial recognition. Achieved a **94.5% recognition accuracy**, enabling real-time, contactless attendance marking with seamless CSV integration.

---

##  Features

-  **94.5% Accuracy** in real-time face recognition  
-  **Live webcam-based detection** using OpenCV  
-  **CSV-based automated attendance tracking**  
-   Supports **diverse datasets** using dynamic CSV data extraction  
-    GUI support via `pblgui.py` for interactive control

---

##Technologies Used

- **Python 3**
- **OpenCV**
- **Pandas**
- **face_recognition**
- **NumPy**
- **Tkinter (for GUI)**

---

##Project Structure

| File / Folder         | Description                                                       |
|-----------------------|-------------------------------------------------------------------|
| `main.py`             | Main script for facial recognition and attendance logging         |
| `smart_attendance.ipynb` | Jupyter Notebook version for testing and debugging               |
| `pblgui.py`           | GUI interface for controlling the attendance system               |
| `LICENSE`             | Project license (MIT)                                             |
| `README.md`           | Project overview and setup guide                                  |

---

##How It Works

1. System captures **live video** from the webcam.
2. Detects and **recognizes faces** using stored images.
3. On successful recognition, logs attendance into a **CSV file**.
4. GUI option available to start/stop attendance tracking interactively.

---

##Installation

###Prerequisites

Ensure Python and pip are installed, then install the required packages:

```bash
pip install opencv-python face_recognition pandas numpy
```

### Clone the Repository

```bash
git clone https://github.com/your-username/smart-attendance.git
cd smart-attendance
```

---

## Usage

### Run from CLI:

```bash
python main.py
```

### Run with GUI:

```bash
python pblgui.py
```

Attendance will be automatically saved in `Attendance.csv`.

---

##  Sample CSV Output

| Name     | Date       | Time     |
|----------|------------|----------|
| Sanuth   | 2025-04-14 | 09:15 AM |
| Sai      | 2025-04-14 | 09:18 AM |

---

## Contributions

Contributions, feedback, and improvements are welcome!

1. Fork the repository
2. Make your changes
3. Submit a pull request

---

## License

This project is licensed under the [MIT License](./LICENSE).

---

