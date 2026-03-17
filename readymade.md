# .C OS

.C OS is a lightweight experimental operating system project built from scratch.  
It combines a custom real‑time kernel (written in C) with a futuristic UI layer (JavaFX) to showcase a hybrid shell inspired by Windows, Android, and iOS.

---

## 🚀 Features
- Custom bootloader in Assembly
- Real‑time kernel in C
- Lightweight design for older hardware
- Futuristic UI with neon buttons, floating taskbar, and search box
- Runs inside QEMU for easy testing

---

## 🛠 Tools Used
- **WSL (Windows Subsystem for Linux)** on Windows 11
- **Compilers**: `gcc`, `make`, `nasm`, `ld`
- **Bootloader/ISO tools**: `grub-pc-bin`, `xorriso`, `grub-mkrescue`
- **Virtualization**: `qemu-system-x86`
- **Languages**: Assembly (bootloader), C (kernel), Java (JavaFX UI)
- **Editors**: nano, VS Code

---

## 📖 Process
1. Set up WSL on Windows 11 with Ubuntu/Mint XFCE.
2. Wrote a minimal bootloader in Assembly.
3. Developed a real‑time kernel in C with scheduler placeholders.
4. Compiled kernel using `gcc` and linked with `ld`.
5. Built bootable ISO using `grub-mkrescue`.
6. Tested in QEMU to verify boot messages.
7. Designed JavaFX UI with neon buttons and floating taskbar.
8. Captured screenshots of QEMU boot and UI demo.

---

## 🎯 Purpose
- Learn OS development from scratch (bootloader, kernel, UI integration).
- Experiment with real‑time kernel concepts like task scheduling.
- Showcase a futuristic hybrid shell with neon UI.
- Make a lightweight OS that runs on older hardware.
- Blend aesthetics with functionality for a unique vision.

---

## 📸 Screenshots
*(Add your QEMU boot screenshot and JavaFX UI screenshot here)*

---

## ▶️ How to Run
```bash
make
make run