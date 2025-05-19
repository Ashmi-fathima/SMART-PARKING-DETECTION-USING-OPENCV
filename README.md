# SMART-PARKING-DETECTION-USING-OPENCV
Here’s a polished GitHub project description (README content) for your Smart Parking Detection using OpenCV and YOLO:

⸻

Smart Parking Space Detector using YOLO and OpenCV

Real-time parking space monitoring powered by YOLO and OpenCV

Overview

This project leverages YOLO (You Only Look Once) object detection models and OpenCV to identify and monitor vacant and occupied parking spaces in real-time. Designed for smart city infrastructure and efficient parking lot management, the system offers high-accuracy detection and can work with both live camera feeds and video files.

⸻

Features
	•	Real-time Parking Detection using YOLOv4 or YOLOv8
	•	OpenCV Integration for efficient image processing
	•	Bounding Box Detection for visual feedback on parked vehicles
	•	Customizable Parking Zone Mapping
	•	Supports Live Camera Feeds & Recorded Videos
	•	Modular and Scalable Codebase

⸻

Installation

1. Clone the Repository

git clone https://github.com/prajesdas/Smart-Parking-Space-Detector-using-YOLO-and-OpenCV.git
cd Smart-Parking-Space-Detector-using-YOLO-and-OpenCV

2. Install Dependencies

pip install -r requirements.txt

3. Download YOLO Weights
	•	Download YOLOv4 weights from the official YOLO website
	•	Or use a pre-trained YOLOv8 model from Ultralytics
	•	Place the weights inside the models/ directory

⸻

Usage

For a video file:

python detect_parking.py --source path/to/video.mp4

For live webcam feed:

python detect_parking.py --source 0



⸻

Project Structure

SMART PARKING DETECTOR/
├── models/              # YOLO model weights  
├── data/                # Parking lot images/videos  
├── utils/               # Helper functions  
├── detect_parking.py    # Main script for detection  
├── requirements.txt     # Dependencies  
└── README.md            # Project documentation  



⸻

Future Enhancements
	•	Mobile app integration for real-time parking availability
	•	Cloud-based storage for long-term parking analytics
	•	License plate recognition for added security and monitoring

⸻

Contributing

Pull requests are welcome! If you’d like to contribute, please open an issue first to discuss your ideas.

⸻

License

This project is licensed under the MIT License.
Feel free to use, modify, and distribute it.

⸻
