
# 📱 Mobile Incoming Call Indicator

A hardware-based RF signal detection circuit that provides a **visual indication of mobile-phone activity** using an inductive pickup element, transistor amplifier, and **NE555 timer**.

The project was developed as part of the **Network Theory Laboratory** in the Department of Electronics and Instrumentation Engineering at **National Institute of Technology Agartala**.

---

## 📸 Project Prototype

![Mobile Incoming Call Indicator](images/Circuit.jpg)

The above image shows the implemented circuit assembled on a breadboard using discrete electronic components and an NE555 timer.

---

## 🎯 Objective

The objective of this project is to detect RF signals emitted by a nearby mobile phone and generate a visual indication through an LED.

The circuit is particularly useful in situations where a mobile phone may be kept in silent or vibrate mode but its RF activity still needs to be detected.

---

## ⚙️ Working Principle

The circuit operates through the following stages:

```text
Mobile Phone RF Activity
          ↓
   Pickup Coil / Antenna
          ↓
     Signal Detection
          ↓
       Transistor
     Amplification
          ↓
      NE555 Timer
          ↓
       LED Output
          ↓
   Visual Indication
```

### 1. RF Signal Detection

When a mobile phone communicates with a cellular network, it emits radio-frequency signals. The project report describes the relevant RF range as approximately **900 MHz–1800 MHz**, depending on the network band.

### 2. Pickup Coil / Antenna

The inductive pickup element detects electromagnetic activity from a nearby mobile phone.

### 3. Signal Conditioning

The detected signal is processed so that it can activate the transistor stage.

### 4. Transistor Amplification

The transistor responds to the detected signal and acts as a switching/amplifying stage.

### 5. NE555 Timer

The amplified signal triggers the **NE555 timer**, which generates the required output signal.

### 6. LED Indication

The output of the timer drives the LED, producing a visible indication when the circuit detects mobile-phone RF activity.

---

## 🔌 Hardware Components

The project report lists the following major components:

| Component              | Specification            |
| ---------------------- | ------------------------ |
| NE555 Timer IC         | 555 Timer                |
| Resistor               | 100 kΩ                   |
| Resistor               | 3.9 kΩ                   |
| Resistor               | 1 MΩ                     |
| Polyester Capacitor    | 100 nF, 63 V             |
| Electrolytic Capacitor | 220 µF, 25 V             |
| NPN Transistor         | Approx. 100 mA, 45 V     |
| Inductive Element      | Pickup coil / inductor   |
| LED                    | High-brightness LED      |
| Breadboard             | Prototype implementation |
| Jumper Wires           | Circuit connections      |

The component list is based on the submitted laboratory project documentation.

---

## 🧩 Circuit Diagram

![Circuit Diagram](images/circuit-diagram.png)

The circuit uses the pickup element to detect RF activity, a transistor stage for signal processing, and an NE555 timer for generating the output indication.

The circuit diagram is included in the project documentation on page 5.

---

## 🔬 Working

The complete operating sequence is:

**RF emission → pickup coil detection → signal conditioning → transistor activation → NE555 triggering → LED indication**

According to the project documentation, the detected RF signal is picked up by the coil/antenna and subsequently processed through the transistor stage. The amplified signal activates the indicator circuit.

The final output is a visual indication through the LED.

---

## 🛠️ Technologies / Concepts Used

* Analog Electronics
* Network Theory
* RF Signal Detection
* Electromagnetic Induction
* Transistor Switching
* NE555 Timer
* Monostable Timer Configuration
* Signal Conditioning
* Breadboard Prototyping
* Electronic Circuit Design

---

## 💡 Applications

The project can be used as a basic mobile-phone RF activity detector in environments such as:

* Homes and offices
* Conference rooms
* Laboratories
* Examination environments
* Areas where mobile-phone activity needs to be indicated

The project documentation also discusses detection of mobile-phone activity from a short distance.

---

## 🚀 Future Scope

Possible improvements include:

* Improving detection sensitivity
* Increasing detection range
* Designing a compact PCB version
* Adding an audible buzzer
* Improving RF filtering
* Using a more sensitive RF detection stage
* Adding a calibrated signal-strength indicator
* Developing a portable enclosure
* Improving reliability across different cellular frequency bands

The project documentation specifically discusses the use of a pickup coil, transistor amplification, NE555 timer, and high-brightness LED as the core architecture.

---

## 👥 Team

**Group 7 — Department of Electronics and Instrumentation Engineering**

* Dhirendra Sahani
* **Anuradha Kumari**
* Abhishek Kumar
* Anjali Patel
* Saumya Shreya
* Aman Kumar

National Institute of Technology Agartala.

---

## 📚 References

The project documentation references:

* Fundamentals of Electric Circuits — Charles K. Alexander & Matthew N. O. Sadiku
* RoboCraze
* Robu
* YouTube tutorials
* Other online technical resources

---

## 📄 Project Documentation

The complete project report and presentation can be found in the `documentation/` and `presentation/` directories.

---

## ⭐ Key Takeaway

This project demonstrates how a combination of **RF signal detection, transistor-based signal processing, and an NE555 timer** can be used to create a simple hardware-based mobile-phone activity indicator.

**Built as an academic hardware prototype using a breadboard and discrete electronic components.**
