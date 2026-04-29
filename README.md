# 🤖 Line Follower Robot (Arduino Nano | 8 IR Sensors | PID Control)

---
<img width="2400" height="1800" alt="image" src="https://github.com/user-attachments/assets/44b918e9-4b6c-4e75-84fd-1954ef320048" />

## 📌 Overview
This project is a **Line Follower Robot (LFR)** designed and developed using **Arduino Nano**.  
It uses an **8-channel IR sensor array (Pololu sensors)** along with a **PID control algorithm** to ensure smooth, stable, and high-speed line tracking.

The robot is built for **robotics learning, embedded systems practice, and competition-level performance**.

---

## ⚙️ Hardware Components

- Arduino Nano  
- Breadboard  
- N20 DC Motors (600 RPM)  
- IR Sensor Array (Pololu 8-channel)  
- Motor Driver Module (L298N or equivalent)  
- LiPo Battery (2200mAh, 22.2V)  
- 0.96" OLED Display  
- Kill Switch (Emergency Power Cut)  
- Functional Push Button (Mode Control)  

---

## 💻 Software & Tools

- Arduino IDE  
- C / C++ Programming  
- PID Control Algorithm  
- Embedded Systems Development  
- Sensor Calibration Techniques  

---

## 🧠 Key Features

- 8-sensor high-precision line detection  
- PID-based smooth motion control  
- Fast response for sharp turns and curves  
- OLED display for real-time system feedback  
- Push button for mode selection  
- Kill switch for safety operation  
- Stable and reliable performance on complex tracks  

---

## 🔧 Working Principle

1. IR sensors detect the position of the line on the track  
2. Arduino Nano reads sensor inputs in real time  
3. PID algorithm calculates deviation from the center  
4. Motor speeds are adjusted dynamically based on correction  
5. Robot continuously stabilizes itself to follow the line  

---

## 📂 Project Structure
Line-Follower-Robot/
│
├── src/
│   └── line_follower.ino        
│
├── hardware/
│   ├── circuit_diagram.png      
│   └── robot_image.jpg          
│
├── docs/
│   └── project_report.pdf       
│
├── images/
│   ├── setup.jpg               
│   └── testing.jpg             
│
├── README.md                    
└── LICENSE                     
---

## 🚀 How to Run

1. Open the project in **Arduino IDE**
2. Connect Arduino Nano via USB
3. Select the correct board:
   - Board: Arduino Nano  
   - Processor: ATmega328P  
4. Install required libraries (if any)
5. Upload the code to Arduino Nano
6. Power the robot using LiPo battery (22.2V)
7. Place the robot on a track and start operation

---

## ⚠️ Safety Notes

- Always use the **kill switch before handling the robot**
- Handle **22.2V LiPo battery carefully**
- Ensure proper wiring to avoid short circuits
- Double-check motor and sensor connections before powering ON

---

## 📸 Demo

- Add robot running video  
- Add circuit diagram image  
- Add sensor layout image  

---

## 👨‍💻 Author

**A F M Atik Bokhtiar Jarif**

- GitHub: https://github.com/afmjarif  
- LinkedIn: https://www.linkedin.com/in/afmjarif  
- Email: afmjarif@gmail.com  

---

## 🏆 Achievements & Purpose

This project demonstrates practical experience in:
- Embedded Systems  
- Robotics Engineering  
- PID Control Systems  
- Sensor-based Automation  

It is suitable for **robotics competitions, academic evaluation, and portfolio showcase**.

---

## 🔮 Future Improvements

- Implement obstacle avoidance system  
- Add wireless control (Bluetooth / WiFi)  
- Improve PID auto-tuning system  
- Upgrade to PCB-based design  
- Optimize speed for competition-level tracks  

---

## 🏁 Conclusion
This Line Follower Robot showcases a strong integration of **hardware and software engineering**, combining sensors, control systems, and embedded programming to achieve autonomous navigation.
