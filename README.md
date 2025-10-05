# 🎥 AI Event-Based Video Recorder

This project demonstrates **event-based video recording** using a mock AI event detector.  
When an event (e.g., overspeed, lane departure, sudden brake) is detected, the system saves a **30-second video clip** — including 15 seconds before and 15 seconds after the event — along with simulated GPS metadata.

---

## 🚀 Features

- Continuous **video buffering** using OpenCV  
- **Mock AI event detection** (easily replaceable with YOLO)  
- **Event-based video saving** (15s before + 15s after)  
- **Metadata logging** (JSON: event type, timestamp, GPS, file path)  
- Optional **Flask API** to list and download clips  

---

## 🧱 Folder Structure

