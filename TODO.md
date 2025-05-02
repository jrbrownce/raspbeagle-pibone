# ✅ Raspbeagle PiBone – Project TODO

This document tracks the planned features, experiments, and improvements for the Raspbeagle PiBone embedded Linux lab.

---

## 🧱 Phase 1: Environment Setup

- [ ] Flash Debian onto Raspberry Pi 3 and BeagleBone Black
- [ ] Install build-essential, kernel headers, and development tools
- [ ] Enable GPIO pin control on both platforms
- [ ] Verify serial/UART connectivity between boards (optional)
- [ ] Create minimal "Hello Kernel Module" on both boards

---

## ⚙️ Phase 2: GPIO + Kernel Module Development

- [ ] Build kernel module that toggles GPIO output (LED)
- [ ] Add `/proc` or `/sys` interface to change GPIO state from user space
- [ ] Test interrupt-driven input (e.g., button press changes behavior)
- [ ] Log all module messages with `dmesg`

---

## 🧪 Phase 3: Firmware-Style Experiments

- [ ] Use Arduino Uno to generate timed pulse signals to test edge detection
- [ ] Read signal input via BeagleBone or Pi GPIO interrupt
- [ ] Use LCD to display state changes or counters (bonus)
- [ ] Simulate I2C/SPI communication with Arduino as slave

---

## 🧠 Phase 4: PRU Real-Time Experiments (BeagleBone Only)

- [ ] Set up PRU toolchain on BeagleBone Black
- [ ] Write basic PRU firmware to blink LED independently
- [ ] Create user-space app to communicate with PRU
- [ ] Benchmark PRU timing accuracy vs Linux kernel delays

---

## 📈 Stretch Goals & Future Ideas

- [ ] Create a virtual character device (e.g., `/dev/pibone_test`) that simulates a sensor
- [ ] Implement a ring buffer in kernel space for GPIO events
- [ ] Build a cross-compiled toolchain for faster dev on host PC
- [ ] Try bit-banging a protocol from PRU or GPIO pins

---

## 🧾 Documentation Tasks

- [ ] Document BeagleBone and Pi GPIO header pinouts in `/docs`
- [ ] Create wiring diagrams in `/hardware-diagrams`
- [ ] Write setup guide and command reference for each platform
- [ ] Add README badges, table of contents, and build instructions

---

## 📌 Notes

- Prioritize real GPIO interaction first
- Keep kernel-space work clean and minimal — use `printk()` sparingly
- Push working modules to GitHub with comments + usage notes
