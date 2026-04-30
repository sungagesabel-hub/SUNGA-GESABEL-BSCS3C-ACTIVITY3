🎥 Live Object Detection with YOLOv8 + Streamlit
This project is a real-time object detection web app using Streamlit, YOLOv8, and WebRTC camera streaming. It detects and tracks objects live using your webcam.

🚀 Features
🎯 Real-time object detection using YOLOv8 (yolov8n.pt)
📷 Live webcam streaming (WebRTC)
🧠 Object tracking support
⚡ Fast performance with model caching
🖥️ Web-based interface (no installation needed for users)

🛠️ Tech Stack
Streamlit
Ultralytics YOLOv8
OpenCV
streamlit-webrtc
PyAV

📁 Project Structure
.
├── app.py
├── requirements.txt
├── yolov8n.pt   (optional – auto-download if not included)
└── README.md

⚙️ Installation (Local Run)
1. Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install dependencies
pip install -r requirements.txt
3. Run the app
streamlit run app.py

📦 requirements.txt
Make sure your requirements.txt contains:
streamlit
streamlit-webrtc
ultralytics
opencv-python
av
🤖 How it works
Loads YOLOv8 model:
YOLO("yolov8n.pt")
