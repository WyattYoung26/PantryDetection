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
- **Item status updates:**  
   - Automatically logs when items are removed or returned to the pantry. 

---

## 🛠️ Tech Stack  
- **YOLO (You Only Look Once):** Deep learning model for real-time object detection.
- **Python:** Core language for integrating the YOLO model with the camera feed.  
- **TensorFlow/Keras (optional):** To train or fine-tune custom object detection models if needed.

---

## 🧩 How It Works  

1. **Object Detection:**  
   - The YOLO model identifies and labels pantry items in the camera feed.  
   - Detected items are logged with key information like their **name** on the shelf 

2. **Item Movement Detection:**  
   - When an item is removed or placed back, the system automatically updates the inventory status.  
   - This provides real-time tracking of pantry usage.

---
