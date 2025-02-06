# pykernel-zero
Custom Minimal Operating System in Python (Sort of)
A minimal “OS” environment booting directly into Python (MicroPython), designed for low-level experimentation. 

## Overview
This project uses [MicroPython](https://micropython.org/) on a microcontroller (e.g., ESP32, Raspberry Pi Pico, STM32). When the device powers on, it launches directly into a MicroPython REPL or runs the `main.py` script automatically—effectively acting like a tiny “bare-metal” Python environment.

### Features (Planned)
- Minimal boot to MicroPython REPL.
- Basic file I/O (on-device filesystem).
- Simple shell commands (`ls`, `cat`, etc.).
- Optional text editor or small “OS-like” menu.

## Getting Started

1. **Choose a Board**: ESP32, STM32, Raspberry Pi Pico, etc.  
2. **Flash MicroPython**:
   - Download the appropriate firmware from [MicroPython Downloads](https://micropython.org/download/).
   - Use a tool like `esptool.py` (for ESP32) or drag-and-drop `.uf2` files (for RP2040 boards).
3. **Clone and Copy**:
   ```bash
   git clone https://github.com/youruser/barepy.git
   cd barepy

