🕶️ Face Anonymizer using MediaPipe & OpenCV

A Python-based Face Anonymization system that detects human faces and automatically blurs them in images, videos, and live webcam streams using MediaPipe Face Detection and OpenCV.

This project demonstrates a complete computer vision pipeline including face detection, bounding box processing, and real-time anonymization.

🚀 Features

✅ Face detection using MediaPipe

✅ Face anonymization using Gaussian blur

✅ Supports:

📷 Image files

🎞️ Video files

🎥 Live webcam feed

✅ Real-time processing

✅ Command-line argument support

✅ Clean and modular code

🛠️ Technologies Used

Python 3.11

OpenCV

MediaPipe

NumPy

Argparse

📁 Project Structure
Face_Anonymizer/
│
├── main.py
├── data/
│   ├── image.png
│   └── testvideo.mp4
│
├── output/
│   ├── output.png
│   └── output.mp4
│
├── venv/
└── README.md

⚙️ Installation
1️⃣ Clone the repository

git clone https://github.com/your-username/Face_Anonymizer.git
cd Face_Anonymizer

2️⃣ Create virtual environment (Python 3.11 recommended)
py -3.11 -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
pip install mediapipe==0.10.9 opencv-python numpy

▶️ How to Run
📷 Image Mode
python main.py --mode image --filePath ./data/image.png


📤Output saved as:

output/output.png


🎞️ Video Mode
bash
Copy code
python main.py --mode video --filePath ./data/testvideo.mp4
📤 Output saved as:

lua
Copy code
output/output.mp4
🎥 Webcam Mode
bash
Copy code
python main.py --mode webcam
🛑 Press q to quit webcam


