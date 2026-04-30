**Available Languages:** [English](README.md) | [Türkçe](README_TR.md)

# Hi there 👋, I'm Emir Aydin.

I'm a Second-year Electrical & Electronics Engineering student @ Marmara University, focused on embedded systems and digital design.  
🔍 I'm open to embedded systems / firmware internships in İstanbul & Bursa.

---

## Projects

### [Dual-MCU Gateway System (Internship Project)](https://github.com/EmirAydin48/dual-mcu-gateway-system) (Case Study)
Fault-tolerant telemetry gateway designed to modernize legacy equipment without disrupting real-time control loops.

- **Objective:** Adding cloud connectivity to legacy devices while preserving deterministic real-time behavior.
- **Architecture:** Designed a dual-MCU system where ESP32 handles networking and STM32 runs the real-time control/telemetry logic.
- **Key Design Work:**
  - Built a non-blocking telemetry pipeline using DMA-driven UART to send data to the server
  - Built a non-blocking command execution pipeline that processes remote commands without stalling the main loop.
  - Built an update pipeline that downloads an update from the server and stores the firmware in an external flash memory.
  - Added a bootloader that checks the update integrity and installs the downloaded firmware. 
- **Tech stack:** C, FreeRTOS, TinyCrypt (AES-CMAC/CTR), STM32 HAL

---

### [FPGA-Based Hardware Cryptography Circuit (Research)](https://github.com/EmirAydin48/VHDL-Hardware-Cryptographic-Engine)
Exploration of cryptographic structures and implementation tradeoffs on FPGA.

- **Project:** Custom cryptographic core synthesized on an Artix-7 FPGA.
- **Key engineering work:** Implemented a Feistel network and NLFSR-based components.
- **Tech stack:** VHDL, Vivado, Logisim, Digital Logic  

---

### [SunflowerBot: FPGA Solar Tracking System (Robotics)](https://github.com/EmirAydin48/VHDL-Solar-Tracking-System)
Hardware-accelerated autonomous control system inspired by heliotropic behavior.

- **Project:** Tracking system that orients toward dominant light sources using FPGA-based control.
- **Key engineering work:**
  - Implemented the control loop fully in hardware (no MCU in the loop) to exploit parallelism and precise timing.
  - Added a custom low-pass filter for signal conditioning.
  - Wrote a bare-metal HD44780 LCD driver with microsecond-level timing.
- **Tech stack:** VHDL, XADC, PWM generation  

---

## Skills

- **Embedded / Firmware:** C, FreeRTOS, STM32 HAL, ESP-IDF  
- **Digital Design:** VHDL, Vivado, FPGA (Artix-7 / Basys 3), Logisim  
- **Interfaces & Peripherals:** UART, SPI, I2C, DMA, ADC, Timers, PWM 
- **Debug / Bring-up:** ST-LINK (SWD), UART logging, oscilloscope, board-level debugging

---

## 📫 **Contact:** [LinkedIn](https://linkedin.com/in/emir-aydin-7b33f48) | [Email](mailto:emiraydin2448@gmail.com)

