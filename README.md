# 🌱 Water Sprinkler Add-On (for Lettusee)

The **Water Sprinkler App** is an add-on built on top of the **Lettusee farming management system**.  
It reuses the same Firebase backend and APK to avoid licensing restrictions, while remaining fully functional and independent in features.  

This project was fully developed by **Gabriel Marcial A. Reyes**.


## 🚀 Features

- **Timer-based Scheduling**  
  - Set **start and stop times** with a specific date to create a watering queue.  
  - Automatically activates the sprinkler at the scheduled times.

- **Force Controls**  
  - **Force ON** – immediately starts spraying water.  
  - **Force OFF** – immediately stops the pump, bypassing the timer.  

- **Queue Management**  
  - **Remove All** – clears all scheduled timers in sequence.  

- **Connectivity**  
  - Works over **WiFi only**.  
  - If offline, you can still set timers locally, but they won’t update Firebase until reconnected.

---

## 📱 User Manual

1. Enter **time in**, **time out**, and **date** to schedule a watering queue.  
2. Use **Force ON/OFF** to override the timer instantly.  
3. Use **Remove All** to clear existing schedules.  
4. Ensure the device is connected to WiFi so the app can sync with Firebase.  

---

## ⚙️ Device Manual

- **Power Supply**  
  - ESP32: powered by **2× 18650 batteries**, lasts for several days.  
    - Auto-sleeps when idle to save power.  
  - Water Pump: powered by **4× AAA batteries**, lasts **1–2 hours** under continuous spraying.  

- **Operation**  
  - Place the pump **underwater**.  
  - It will automatically spray based on active timers.  

- **Prototyping Methodology**  
  - Designed for flexibility and upgrades.  
  - Components (pump, battery, controller) can be replaced or customized.  

---

## 📦 Build Information

- **Base Application:** Lettusee (Unity + Firebase)  
- **Platform:** Android (APK)  
- **Backend:** Firebase Realtime Database  
- **Hardware:** ESP32, water pump, batteries  

---
<img width="789" height="498" alt="image" src="https://github.com/user-attachments/assets/92cff907-e00b-4fde-b243-2f41cbdd5726" />

## 👨‍💻 Developer

Developed by **Gabriel Marcial A. Reyes**  
- GitHub: [github.com/gmseyer](https://github.com/gmseyer)  
- Project: Add-on to [Lettusee](https://github.com/gmseyer/lettusee)  

---
