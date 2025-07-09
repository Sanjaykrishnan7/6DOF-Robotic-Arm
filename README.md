
# 🤖 Design and Implementation of a 6DOF Robotic Arm

This project presents the design and implementation of a **6 Degrees of Freedom (6DOF) robotic arm**, a multi-joint manipulator capable of performing complex 3D tasks with precision and flexibility. Built using an Arduino Nano and controlled wirelessly via Bluetooth (HC-05), the robotic arm demonstrates real-time movement across six axes and showcases applications across industries like manufacturing, medicine, research, and education.

---

## 📌 Project Overview

A **6DOF robotic arm** is a mechanical device that can move in six independent directions: three translational (X, Y, Z) and three rotational (roll, pitch, yaw). These six axes mimic the movement capabilities of a human arm, allowing for high flexibility and dexterity in automated tasks.

### 🎯 Objective
To build a low-cost, Arduino-controlled 6DOF robotic arm that can be wirelessly operated using Bluetooth and used for industrial and educational demonstrations.

---

## 🛠️ Components Used

| Component               | Description                              |
|------------------------|------------------------------------------|
| 6DOF Robotic Arm Kit   | Structure with servo motors              |
| Arduino Nano           | Microcontroller unit                     |
| Nano Shield            | Easier interface for connecting devices  |
| HC-05 Bluetooth Module | Enables wireless control                 |
| Buck Converter         | Voltage regulation                       |
| Power Supply & Switch  | System power management                  |
| Jumper Wires           | Wiring and connectivity                  |

---

## 💡 Features

- 🎮 **Bluetooth Control** – Control the arm using mobile apps or serial monitors via HC-05
- ⚙️ **6 Degrees of Movement** – Offers motion in 6 axes for complex positioning
- 🧠 **Arduino-Based** – Open-source and beginner-friendly platform

---

## 🧪 Working Principle

1. The user sends control signals wirelessly via a Bluetooth-enabled device.
2. The HC-05 module receives the signals and transmits them to the Arduino Nano.
3. Arduino interprets the input and sends PWM signals to servo motors in the robotic arm.
4. Each servo motor actuates specific joints, enabling coordinated multi-axis movement.

---

## 🧭 Applications

| Domain             | Use Case Example                                     |
|--------------------|------------------------------------------------------|
| 🏭 Manufacturing    | Assembly, pick-and-place, quality inspection         |
| 🧬 Healthcare       | Surgical simulations, lab automation                 |
| 📦 Warehousing      | Object sorting, automated stacking                   |
| 🔭 Space Research   | Satellite maintenance, planetary exploration         |
| 🎓 Education        | Teaching robotics, control systems, and programming |

---

---

## 👨‍💻 Team Members

- Sanjaykrishnan N V 
- Naveenraj S S  
- Santhosh Adithiya B L  
 
🗓️ **Date of Completion**: 27th March 2024

---

## 🔗 Project Files

| File/Folder        | Description                                  |
|--------------------|----------------------------------------------|
| `Presentation/`    | Project PPT explaining design & importance   |
| `Code/`            | Arduino source code                          |
| `Images/`          | Project visuals and demo photos (optional)   |
| `README.md`        | You're reading it! Project documentation     |

---

## 🚀 Future Enhancements

- Integrate camera module and computer vision for object detection
- Add feedback sensors for closed-loop control
- Build a custom Android app for intuitive control
- Expand to IoT-based cloud-controlled arm

---

## 📥 How to Run

1. Upload the Arduino code from `/Code` folder to Arduino Nano using the Arduino IDE.
2. Power the system with a suitable regulated supply.
3. Pair HC-05 with your phone/PC (default password: `1234` or `0000`).
4. Send commands through a Bluetooth terminal or controller app.
5. Observe the arm moving in response to your inputs!

---

## 📫 Contact

For collaborations, feedback, or questions:
**Sanjaykrishnan NV**  
📧 sanjayramesh462@example.com 

---

> *“Robotics isn’t just about machines – it's about solving real-world problems with engineering creativity.”*



