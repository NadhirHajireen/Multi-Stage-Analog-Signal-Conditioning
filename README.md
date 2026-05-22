# 📻 Multi-Stage Analog Signal Conditioning for AM Radio Audio Output

A multi-stage analog electronics system designed to simulate the **audio output section of an AM radio receiver**, where a weak, noisy demodulated signal is processed into a clean, amplified audio output suitable for headphones or a small speaker.

---

## 📌 Project Overview

In analog communication systems, raw signals from transducers or radio receivers are rarely usable without conditioning. This project focuses on designing and implementing a **multi-stage signal conditioning circuit** that improves signal quality through filtering and amplification.

The system takes a **weak, noisy audio signal** (similar to an AM radio demodulated output) and processes it into a clean, usable audio signal.

---

## 🎯 Objective

To design, build, and test a **three-stage analog signal conditioning circuit** that:

- Removes unwanted frequency components  
- Amplifies weak audio signals  
- Produces a clean output suitable for audio devices (headphones/small speaker)  

---

## ⚙️ System Design (3 Stages)

### 🔹 Stage 1: High-Pass Filter (2 kHz cutoff)
A passive RC high-pass filter is used to remove **low-frequency noise** such as:
- Power line hum  
- Wind noise  
- DC drift components  

👉 Only audio-frequency signals above 2 kHz are allowed to pass.

---

### 🔹 Stage 2: Common Emitter Amplifier (BJT)
A BJT transistor in **common-emitter configuration** is used to:

- Provide voltage amplification  
- Achieve a mid-band gain of **≥ 60**  
- Boost weak filtered signals to usable levels  

The transistor is properly biased to ensure operation in the **active region**.

---

### 🔹 Stage 3: Low-Pass Filter (12 kHz cutoff)
A passive RC low-pass filter is used to remove:
- High-frequency noise  
- Residual carrier signals  
- Unwanted RF interference  

👉 Ensures smooth and clean audio output.

---

## ⚡ Power Supply

- 🔋 9V DC supply  
- Proper biasing network ensures stable transistor operation  

---

## 🧠 Key Components

- 🔌 Resistors & Capacitors (RC filters)
- 🔋 9V DC Power Supply
- 🔺 BJT Transistor (Common Emitter Amplifier)
- 🎛️ Signal source (weak/noisy audio input simulation)
- 🔊 Output load (headphones / small speaker)

---

## 🔬 Testing Methodology

The circuit was tested in stages:

1. Each filter stage was tested independently  
2. Amplifier performance was verified for correct gain  
3. Full system was tested end-to-end  

Oscilloscope measurements were taken at:
- Input signal  
- After high-pass filter  
- After amplifier stage  
- Final output  

---

## 📊 Observations

- Low-frequency noise was significantly reduced after Stage 1  
- Signal amplitude increased after the amplifier stage  
- High-frequency artifacts were removed in Stage 3  
- Final output was clean and suitable for audio playback  

---

## 📈 Key Outcomes

- Successfully implemented multi-stage analog signal conditioning  
- Achieved required amplification (gain ≥ 60)  
- Demonstrated effective filtering using RC networks  
- Produced clean audio output from a noisy input signal  

---

## 🧪 Applications

- 📻 AM radio receiver audio processing  
- 🎤 Sensor signal conditioning  
- 📡 Communication systems  
- 🔬 Analog electronics experimentation  
- 🎧 Audio signal processing circuits  

---

## 👨‍💻 Author

**Nadhir Hajireen**  
🎓 Computer Systems Engineering Student  
🏫 SLIIT  

---

## 📌 Note

This project demonstrates how fundamental analog building blocks—**RC filters and BJT amplification stages**—can be combined to solve real-world signal processing problems in communication systems.
