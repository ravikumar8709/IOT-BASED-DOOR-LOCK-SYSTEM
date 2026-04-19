# 📌 Smart Door Lock System 🔐 (ESP32-CAM Based)

## 🚀 Overview
This project is an IoT-based Smart Door Lock System using ESP32-CAM, enabling remote access, monitoring, and smart security using a camera module and internet connectivity.

---

## 🧩 System Block Diagram

```
Camera  --->  ESP32-CAM  --->  Door Lock
                  |
                  ↓
             WiFi Router  ↔  Internet  ↔  Smartphone
```

---

## 🔍 Explanation

- 📷 Camera captures images/video
- 🧠 ESP32-CAM processes data and controls system
- 📡 WiFi Router connects device to internet
- 📱 Smartphone sends commands and receives alerts
- 🔐 Door Lock is controlled via relay/servo

---

## 🧠 Features

- 🔐 Remote lock/unlock
- 📷 Live video streaming
- 📡 WiFi-based control
- 🚨 Security alerts
- 📱 Mobile access

---

## 🛠️ Tech Stack

- Hardware: ESP32-CAM, Relay, Door Lock
- Software: Arduino IDE
- Libraries: WiFi, ESP32 Camera

---

## ⚙️ Working Flow

1. ESP32 connects to WiFi
2. Camera starts streaming
3. User sends command via mobile
4. ESP32 processes request
5. Door lock opens/closes

---

## 📂 Project Structure

```
Smart-Door-Lock/
│── code/
│   └── esp32_cam.ino
│
│── images/
│   └── block_diagram.png
│
│── README.md
```

---

## ⚙️ Setup Instructions

### 1. Upload Code
- Open Arduino IDE
- Select ESP32-CAM board
- Upload code

### 2. Connect Hardware
- Camera → ESP32-CAM
- Relay → Door Lock

### 3. Run System
- Connect to WiFi
- Open IP in browser

---

## 🚧 Future Improvements

- Face Recognition
- Mobile App
- Cloud Integration

---
## Final model image 
<img width="1078" height="691" alt="image" src="https://github.com/user-attachments/assets/62fa3484-2c5d-414c-bf11-9d73c14de13c" />

## 📧 Contact

Ravi Kumar  
