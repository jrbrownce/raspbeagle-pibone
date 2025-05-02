# 🧠 Raspbeagle PiBone  
*A cross-platform embedded Linux lab using Raspberry Pi & BeagleBone Black*

---

## 📘 Overview

**Raspbeagle PiBone** is a personal firmware and Linux kernel development lab designed to bridge bare-metal embedded techniques with Linux kernel module development. It uses real hardware platforms — the Raspberry Pi 3 and BeagleBone Black — to explore low-level GPIO control, interrupt handling, device drivers, and real-time logic.

This project serves as a portfolio, learning platform, and testbed for custom kernel modules, GPIO drivers, and protocol simulations using C and C++.

---

## 🎯 Goals

- Practice **bare-metal and low-level programming** techniques
- Develop and test **Linux kernel modules**
- Control hardware through **memory-mapped I/O**, `/proc`, and `/sys`
- Use the **BeagleBone PRUs** for real-time control
- Learn cross-platform embedded Linux techniques on real hardware

---

## 🧰 Hardware Used

- ✅ Raspberry Pi 3 Model B  
- ✅ BeagleBone Black Rev C  
- ✅ Arduino Uno (used for simulation and interrupt testing)  
- ✅ LCD display, buttons, breadboard, jumpers, and standard starter kit components  

---

## 🚀 Getting Started

> Coming soon: Build steps and setup guides for both Pi and BeagleBone environments.

- [ ] Flash Debian to Raspberry Pi and BeagleBone  
- [ ] Install kernel headers and development tools  
- [ ] Build and insert your first kernel module  
- [ ] Connect GPIO lines for external signal testing  
- [ ] Optional: Set up UART communication between devices

---

## 📂 Project Structure

| Folder | Description |
|--------|-------------|
| `/kernel-modules` | LKMs, GPIO drivers, and device node experiments |
| `/firmware-tests` | Arduino ISRs, PWM experiments, timing analysis |
| `/docs` | Notes, pinouts, command references |
| `/hardware-diagrams` | Fritzing / PNG circuit layouts (coming soon) |

---

## 📓 Logbook / Dev Journal

> Document your progress here, week by week. This adds credibility and transparency for reviewers or hiring managers.

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
Attribution is appreciated when referencing or building upon this work.

---

📛 **Raspbeagle PiBone** is an original embedded Linux and firmware development project by **Jessie Brown**, combining Raspberry Pi and BeagleBone Black platforms.
