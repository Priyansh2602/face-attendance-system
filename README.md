<h1 align="center">📸 Face Attendance System</h1>

<p align="center">
  Real-time face detection & recognition attendance system built using Python and OpenCV.  
</p>

---

## 🚀 About the Project

This project captures live webcam video, detects faces in real-time, and recognizes individuals based on trained image data. Once recognized, it logs attendance automatically into a file.

<div align="center">
  
🧠 **Face Recognition** using Haar Cascade  
📝 **Attendance Logging** as text/CSV  
📸 **Live Detection through Webcam**  
📁 **Modular Folder Structure**  

</div>

---

## 🗂️ Project Structure
face-attendance-system/

│
├── Attendance/ # Attendance logs

├── StudentDetails/ # Student information

├── TrainingImageLabel/ # Training images folder

├── haarcascade_frontalface_default.xml

└── main.py # Main script to run


---

## 🛠️ Technologies Used

| Tech            | Description                       |
|-----------------|-----------------------------------|
| 🐍 Python       | Core Programming Language         |
| 📷 OpenCV       | Face detection with Haar Cascade  |
| 🧬 face-recognition | LBPH (Local Binary Patterns Histogram)  |
| 🗂️ CSV/Text     | Attendance logging format         |

---

## 🔧 Installation & Setup

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Priyansh2602/face-attendance-system.git
   cd face-attendance-system


⚙️ Install dependencies
• pip install opencv-python


▶️ Run the Project
• python main.py


Make sure your webcam is connected and working.

📋 How It Works

• Loads Haar Cascade classifier for face detection

• Captures frames from webcam

• Detects and recognizes stored faces

• Logs name & timestamp to the Attendance/ folder

📈 Possible Improvements

• Store attendance in a database

• Train on larger datasets for more accuracy

• Notify users with email/report generation

👤 Author

Priyansh Arora

📧 Email: priyansharora9291@gmail.com

🌍 Location: Delhi, India

