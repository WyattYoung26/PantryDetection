Pantry Item Tracker using YOLO and Object Detection

Overview
This project uses YOLO (You Only Look Once), a camera, and object detection to keep track of items in a pantry. The goal is to monitor items based on their shelf life, track when they are taken out, and when they are put back, providing a smart system to manage pantry inventory.

Features
Real-time object detection: Utilizes YOLO for identifying and tracking items in the pantry.
Shelf life monitoring: Tracks the expiration date of items and alerts the user when an item is approaching its shelf life.
Item status updates: Detects when items are removed and placed back into the pantry.
Camera Integration: Uses a camera feed to constantly monitor pantry shelves and detect any changes in item placement.
Tech Stack
YOLO (You Only Look Once): Deep learning model for real-time object detection.
OpenCV: Library for real-time computer vision to capture the camera feed.
Python: Core programming language for integrating YOLO and OpenCV.
TensorFlow/Keras (optional): For training or fine-tuning custom object detection models.
How It Works
Camera Setup: A camera is installed to monitor the pantry shelves. The camera feed is processed by the system to detect and track items.
Object Detection: The YOLO model identifies and labels items in the pantry. Each item is logged with details like its name and position.
Tracking Shelf Life: The system can associate expiration dates with detected items and track them over time.
Item Movement Detection: The system detects when items are removed or placed back, updating the inventory in real-time.
