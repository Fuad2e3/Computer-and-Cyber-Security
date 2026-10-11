<div align="center">

# 🛡️ Computer and Cyber Security
### **C++ Password Strength Analyzer & Threat Simulation Engine**

[![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![Domain](https://img.shields.io/badge/Domain-Cyber_Security-red?style=for-the-badge)](https://en.wikipedia.org/wiki/Computer_security)
[![Interface](https://img.shields.io/badge/Interface-Interactive_CLI-darkgreen?style=for-the-badge)](password_analyzer.cpp)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**An interactive security auditing and brute-force simulation utility designed to analyze cryptographic entropy and vulnerability profiles.**

---

[Explore Features](#-key-features) • [Project Structure](#-project-structure) • [Tech Stack](#-technical-details)

</div>

---

## 📖 Overview
**Computer and Cyber Security** is a native **C++** security laboratory tool featuring a specialized **Password Strength Analyzer and Ethical Hacking Simulator**. Designed to demonstrate password entropy vulnerabilities, dictionary attack surfaces, and brute-force cracking resistance, it provides educational insights into credential defense mechanisms through real-time telemetry and ANSI color terminal animations.

---

## ✨ Key Features

- 🔐 **Entropy & Complexity Scorer:** Dynamically evaluates character distribution (lowercase, uppercase, digits, symbols), length, and repeating sequences.
- 🎯 **Attack Vector Prediction:** Identifies whether a credential is most susceptible to rainbow tables, dictionary attacks, or brute-force enumeration.
- ⚡ **Real-Time Crack Simulation:** Simulates an attacker's trial-and-error discovery with live ANSI-colored visual feedback and progressive crack times.
- 🖥️ **Immersive Cyber Terminal UI:** Engineered with custom terminal typing effects, color-coded threat alerts, and vulnerability summaries.

---

## 📁 Project Structure

```text
Computer-and-Cyber-Security/
├── password_analyzer.cpp       # Core analyzer and terminal simulation engine
├── LICENSE                     # MIT License
└── README.md                   # Documentation and usage guide
```

---

## 🛠️ Technical Details

The core security algorithms reside in [`password_analyzer.cpp`](file:///c:/Users/fuadk/Documents/GitHub/DEMO/Computer-and-Cyber-Security/password_analyzer.cpp):
- `analyzePassword()`: Multi-factor scoring algorithm weighting entropy, length, and collision probability.
- `simulateCrack()`: Realistic cryptographic crack duration simulation based on candidate character sets ($N^L$).
- `typeText()` & `printColored()`: Low-level POSIX/Win32 ANSI escape sequence renderer.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>
