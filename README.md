# 🕹️ SplitDeck Zero
*A zero-compromise controller built on a near-zero budget.*

## 📌 Overview
**SplitDeck Zero** is an open-source custom game controller project focused on achieving **premium controller features at the lowest possible cost**.

Instead of designing an expensive custom enclosure and PCB, this project **reuses a cheap off-the-shelf wired controller** and replaces its internal electronics with a **Super Mini nRF52 microcontroller**, while adding advanced features typically found in high-end controllers.

The philosophy is simple:

> Reuse what already exists.  
> Replace only what matters.  
> Learn everything in the process.

---

## 🎯 Project Goals
- Build a **feature-rich controller at a fraction of the cost**
- Reuse an existing controller shell and buttons to reduce waste
- Learn and experiment with **nRF52, BLE HID, and embedded systems**
- Keep the project **beginner-friendly, modular, and hackable**
- Avoid custom PCBs where possible

---

## 🧠 Inspiration
This project is inspired by **OpenSplitDeck**, but with a different approach:

| OpenSplitDeck | SplitDeck Zero |
|---------------|---------------|
| Custom enclosure & PCB | Reused controller shell |
| Higher cost | Ultra low-cost focus |
| Split deck layout | Traditional controller layout |
| Advanced enthusiast build | Budget-first learning build |

---

## 🧩 Hardware Used
- **Controller Shell & Buttons**  
  Reused from a low-cost wired game controller (₹500 range)

- **MCU**  
  Super Mini nRF52

- **Planned Add-ons**
  - Display (OLED / LCD)
  - Gyroscope / motion sensing
  - Vibration motor
  - Macro support
  - Battery + charging module
  - Bluetooth Low Energy (HID)
  - USB wired mode fallback

---

## ✨ Planned Features
- 🎮 Standard gamepad input
- 📟 On-device display for profiles / status
- 🧠 Macro recording and playback
- 🌀 Gyro aiming / motion input
- 🔊 Vibration feedback
- 🔋 Battery-powered wireless mode
- 🔌 USB wired mode
- ⚙️ Configurable firmware

> ⚠️THIS IS IN INITIAL PHASE.

---

## 🛠️ Software & Firmware
- Arduino-based development (initial phase)
- nRF52 BLE HID implementation
- Button matrix scanning
- Modular firmware design (planned)

---
