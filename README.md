# 🌍 An Earthquake Alert System using Internet of Things (IoT)

This repository contains the **IEEE conference paper** titled  
**“An Earthquake Alert System using Internet of Things”**, published at the  
**2024 10th International Conference on Communication and Signal Processing (ICCSP)**.

The work presents a **low-cost, real-time earthquake detection and alert system** using IoT sensors and microcontrollers to enhance disaster preparedness and early warning capabilities.

---

## 📌 Publication Details

- **Title:** An Earthquake Alert System using Internet of Things  
- **Conference:** 2024 10th International Conference on Communication and Signal Processing (ICCSP)  
- **Location:** Melmaruvathur, India  
- **Year:** 2024  
- **Publisher:** IEEE  
- **DOI:** 10.1109/ICCSP60870.2024.10544248  

🔗 **IEEE Xplore Link:**  
https://ieeexplore.ieee.org/document/10544248

---

## 🧠 Abstract (Summary)

Earthquakes pose a significant threat to human life and infrastructure, especially in densely populated regions.  
This work proposes an **Arduino-based earthquake alert system** using a **3-axis accelerometer (ADXL335)** to detect seismic vibrations in real time.

The system continuously monitors acceleration values along the **X, Y, and Z axes**, compares them against predefined threshold values, and triggers **visual (LED), auditory (buzzer), and textual (LCD)** alerts when abnormal vibrations are detected.

The proposed solution is:
- Cost-effective
- Easy to deploy
- Suitable for both urban and remote areas
- Low power consuming

This system enhances **early warning mechanisms**, enabling faster human response during seismic events.

---

## 🏗️ System Architecture

The system consists of:
- **ADXL335 Accelerometer** – vibration sensing
- **Arduino Uno** – data processing & control
- **16×2 LCD Display** – real-time alert messages
- **Buzzer & LED** – immediate warning signals
- **Processing IDE** – visualization of vibration data

📌 When sensor readings exceed predefined thresholds, the system:
1. Detects abnormal seismic activity
2. Activates buzzer and LED
3. Displays alert message on LCD
4. Sends data for visualization and analysis

---

## ⚙️ Key Technologies Used

- Internet of Things (IoT)
- Arduino Uno
- ADXL335 3-Axis Accelerometer
- Embedded Systems
- Signal Processing
- Real-time Monitoring
- Processing IDE (Visualization)

---

## 📊 Results & Observations

- The system successfully differentiates between **normal vibrations and earthquake-level vibrations**
- Alerts are generated immediately when threshold values are crossed
- Vibration data is visualized graphically for further analysis
- The earthquake magnitude can be estimated using accelerometer readings

📐 Magnitude Formula Used:

Magnitude = log10(√(X² + Y² + Z²)) + 1.5


---

## 🏆 Significance of the Work

- Demonstrates a **low-cost alternative** to traditional seismic stations
- Suitable for household and institutional deployment
- Can be extended to applications like:
  - ATM security
  - Vehicle vibration monitoring
  - Door-break & intrusion detection
- Highlights the role of **IoT in disaster mitigation**

---

## 👨‍💻 Authors

- **N. Vishnu Teja**
- S. P. Akshay  
- K. A. Khaleed  
- C. S. Kumar  
- G. P. Manoj Kumar  
- R. M. Bhavadharini  

School of Computer Science and Engineering  
Vellore Institute of Technology, Chennai, India

---

## ⭐ Note

This repository is created to **showcase the research work and publication**, as the original implementation code and hardware setup were part of academic research.

---

## 📖 Citation

```bibtex
N. V. Teja, S. P. Akshay, K. A. Khaleed, C. S. Kumar, 
G. P. Manoj Kumar and R. M. Bhavadharini, 
"An Earthquake Alert system using Internet of Things," 
2024 10th International Conference on Communication and Signal Processing (ICCSP), 
Melmaruvathur, India, 2024, pp. 1621-1626, 
doi: 10.1109/ICCSP60870.2024.10544248.

