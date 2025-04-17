Advanced Lane Assistant – Self Driving Car Safety System
A smart web application that detects lane lines, nearby vehicles, and recommends safe lane switches using YOLO and OpenCV, with a live video preview, real-time safety stats, and downloadable output.

🚗 Project Description
Advanced Lane Assistant is a Flask-based web app designed to enhance road safety in self-driving cars or driver-assist systems. It:

Detects lane markings in real-time.

Identifies nearby vehicles using YOLOv3.

Calculates vehicle speed using optical flow.

Recommends safe lane changes when current lanes are blocked.

Provides a beautiful, interactive UI with live video streaming, progress bar, and download option.

🔥 Features
✅ Lane detection with ROI and Hough Transform
✅ Vehicle detection using YOLOv3 (cars, buses, trucks)
✅ Curvature and speed estimation
✅ Time-to-collision (TTC) and proximity alerts
✅ Smart lane suggestion (left/right)
✅ Real-time progress tracking
✅ Live preview and processed video download
✅ Modern, responsive UI using Bootstrap and glowing animations

🧠 Tech Stack
Frontend: HTML5, CSS3, Bootstrap 5

Backend: Python, Flask

Computer Vision: OpenCV, YOLOv3

Model Files: yolov3.weights, yolov3.cfg, coco.names
