# 🛒 Pantry Item Tracker using YOLO and Object Detection

## 📋 Overview  
This project leverages **YOLO (You Only Look Once)** object detection, a camera, and real-time tracking to manage pantry inventory.  
The system monitors:  
- **Item usage** (tracking when items are removed or returned).  
- **Smart inventory updates** through a camera feed to ensure your pantry stays organized and well-stocked.

---

## ✨ Features  
- **Real-time object detection:**  
   - Utilizes **YOLO** to detect and track pantry items with high accuracy.  
- **Shelf life monitoring:**  
   - Tracks expiration dates and sends alerts for items nearing their expiration.  
- **Item status updates:**  
   - Automatically logs when items are removed or returned to the pantry.  
- **Camera integration:**  
   - Uses a live camera feed to detect any changes in item placement.  

---

## 🛠️ Tech Stack  
- **YOLO (You Only Look Once):** Deep learning model for real-time object detection.  
- **OpenCV:** Library for real-time computer vision and capturing the camera feed.  
- **Python:** Core language for integrating the YOLO model with the camera feed.  
- **TensorFlow/Keras (optional):** To train or fine-tune custom object detection models if needed.

---

## 🧩 How It Works  

1. **Object Detection:**  
   - The YOLO model identifies and labels pantry items in the camera feed.  
   - Detected items are logged with key information like their **name** and **position** on the shelf.  

2. **Tracking Shelf Life:**  
   - The system can associate expiration dates with items, keeping track of how long they’ve been in the pantry.  
   - Alerts are triggered when an item approaches its expiration date.  

3. **Item Movement Detection:**  
   - When an item is removed or placed back, the system automatically updates the inventory status.  
   - This provides real-time tracking of pantry usage.

---
