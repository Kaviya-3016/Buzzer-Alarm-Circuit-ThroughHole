
# 🔔 Simple Buzzer Alarm Using Through Hole

This project is a simple electronics circuit designed using **EAGLE PCB Design Tool** to create a single-layer through-hole PCB for a buzzer-based alarm system using the **NE555 Timer IC**.

---

## 📘 Overview

The buzzer alarm circuit generates a sound alert using a speaker whenever powered. It uses a 555 timer in astable mode to generate pulses that drive the buzzer. This project is ideal for beginners to learn the basics of PCB design and component interfacing.

---

## 🧩 Components Used (BOM)

| Qty | Value   | Device        | Package      | Designator | Description                |
| --- | ------- | ------------- | ------------ | ---------- | -------------------------- |
| 1   | 0.1uF   | Capacitor     | C025-024X070 | C1         | Capacitor, American symbol |
| 2   | 100uF   | CPOL-USE5     | E5-10.5      | C3, C4     | Polarized Capacitor        |
| 1   | 10uF    | CPOL-USE2     | E2-5         | C2         | Polarized Capacitor        |
| 1   | 15k     | Resistor      | 0204/5       | R2         | Resistor                   |
| 1   | 5.6k    | Resistor      | 0204/5       | R3         | Resistor                   |
| 1   | 1k      | Potentiometer | PT-10        | R1         | Variable Resistor          |
| 1   | NE555N  | IC            | DIL08        | IC1        | 555 Timer IC               |
| 1   | KSS1201 | Speaker       | KSS1201      | SP1        | Alarm/Buzzer               |
| 1   | AB9V    | Battery Clip  | AB9V         | G1         | 9V Battery Clip            |

---

## 🔧 Software Used

* **Autodesk EAGLE 7.5.0 Light**
  Used to design both the schematic and PCB layout of the circuit.

---

## 🖥️ Files Included

* 📄 Schematic Design (`.sch`)
* 📄 Board Layout (`.brd`)
* 📄 BOM (Bill of Materials) text file
* 📷 Schematic and PCB layout images

---

## 📐 PCB Details

* **Layer**: Single Layer
* **Design**: Through-Hole Components
* **Board Dimensions**: 55.88mm × 43.17mm
* **IC Used**: NE555 Timer
* **PCB Features**:

  * Compact layout
  * Clear component labeling
  * Manually routed traces

---

## ⚙️ Working Principle

* The NE555 Timer is configured in **astable mode**.
* It continuously switches between HIGH and LOW states, generating square wave pulses.
* These pulses drive the buzzer (SP1) to produce sound.
* You can control the tone/frequency by adjusting the **potentiometer (R1)**.

---

## ✅ Advantages

* Simple and beginner-friendly
* Easy to assemble using through-hole components
* Reusable design for various 555 timer-based applications

---

## ❌ Limitations

* Fixed buzzer tone (unless modified with different resistor/capacitor values)
* Not suitable for high-frequency or programmable alerts

---

## 📸 Previews

### Schematic

![WhatsApp Image 2025-07-04 at 10 53 45_ed582f4f](https://github.com/user-attachments/assets/bb96d539-42a2-4fc7-857e-306048cbe1d0)


### PCB Layout

![WhatsApp Image 2025-07-04 at 10 53 46_1be86520](https://github.com/user-attachments/assets/8a43797d-873d-4e9e-881d-e5e2acb7ae50)


### BOM

![WhatsApp Image 2025-07-04 at 10 53 46_739d3ecb](https://github.com/user-attachments/assets/ebab43f3-2a02-4956-bf22-30d1550b3443)


---

## 💡 Future Improvements

* Use a programmable microcontroller for custom alarm patterns
* Add motion sensor or light sensor to activate buzzer conditionally
* Convert it into a wearable or enclosure-ready module

---

## 👩‍💻 Author

**Kaviya Murugan**
PCB Design Enthusiast | ECE Engineer | AI Intern @ Infosys Springboard

Feel free to ⭐ the repo or fork it for your own experiments!

---
