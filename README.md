# AI-Based-Real-Time-Fake-Currency-Detection-System
A real-time fake currency detection system using YOLOv4-tiny deep learning model, OpenCV, and Flask web interface. The system detects currency notes through a webcam, classifies them, and provides voice feedback indicating the detected denomination.
Fake-Currency-Detection/
│
├── app.py                # Flask web app
├── detect.py             # YOLO detection script
├── RealFake_Model.h5     # Trained model (optional if using YOLO weights)
├── yolov4-tiny-custom.cfg
├── yolov4-tiny-custom_final.weights
├── classes.names
├── templates/
│   └── index.html
├── static/
│
└── README.md


AI-Based Real-Time Fake Currency Detection
📌 Overview

This project detects real-time currency notes using a webcam and classifies them using a YOLOv4-tiny model. It also provides audio output for detected currency values.

⚙️ Features
Real-time currency detection using webcam
YOLOv4-tiny deep learning model
High confidence threshold (95%) for accuracy
Voice feedback using text-to-speech
Flask-based web interface
FPS display and UI overlay
🛠️ Technologies Used
Python
OpenCV
YOLOv4-tiny
Flask
NumPy
Pyttsx3 (Text-to-Speech)
📷 How It Works
Webcam captures live video
YOLO model processes frames
Detects currency denomination
Displays bounding box + confidence
Speaks detected value using voice
▶️ Installation
git clone https://github.com/your-username/fake-currency-detection.git
cd fake-currency-detection

Install dependencies:

pip install opencv-python numpy flask pyttsx3 imutils
▶️ Run the Project
Run Flask App:
python app.py
Run Detection:
python detect.py
📌 Requirements
Python 3.x
Webcam
YOLO weights and config files
📊 Future Improvements
Improve model accuracy with larger dataset
Add mobile app support
Detect fake vs real classification explicitly
Cloud deployment
👨‍💻 Author :ADITHYA S
