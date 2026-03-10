# 8-Bit-Computer

![Status](https://img.shields.io/badge/Status-Work%20In%20Progress-orange)
![Hardware](https://img.shields.io/badge/Hardware-Discrete%20Logic-blue)

## 📌 Project Overview
This repository documents my ongoing journey of building a fully functional, programmable 8-bit computer from scratch using basic TTL logic chips and breadboards. 

The project is heavily inspired by the incredible [Ben Eater 8-bit CPU tutorial series](https://eater.net/8bit), taking the theoretical concepts of computer architecture and applying them in the physical world.

## 🚀 Current Status: RAM Module (In Progress)
The build is currently halfway through. I have successfully designed, wired, and tested the core computational components and am currently finalizing the Random Access Memory (RAM) module to enable data storage.

### ✅ Completed Modules:
* **Clock Module:** Built with 555 timers. Features an adjustable clock speed and a manual step mode for debugging.
* **Registers (A, B, and Instruction Register):** 8-bit registers built using 74LS173 D-type flip-flops and 74LS245 bus transceivers for reading/writing to the main bus.
* **Arithmetic Logic Unit (ALU):** Capable of adding and subtracting 8-bit numbers using 74LS283 adders and XOR gates. 

### 🚧 Currently Working On:
* **RAM Module & Memory Address Register (MAR):** Integrating SRAM chips (like the 74189) and multiplexers to store and retrieve data/instructions. 

## 📸 Gallery
![20250826_230616](https://github.com/user-attachments/assets/36e5caca-76e3-4fce-9281-3e2e0c0bea64)
![20250826_230608](https://github.com/user-attachments/assets/0f13bf46-32ca-4254-a7aa-9b8ba7324894)
![20251126_093128](https://github.com/user-attachments/assets/26b411a0-4f0f-4df2-b77a-b3ba18df1a95)

## 🛠️ Components & Technologies Used
* **Logic Family:** 7400-series TTL ICs
* **Timing:** NE555 Timers
* **Storage:** SRAM 
* **Tools:** Breadboards, Multimeter, Wire Strippers, lots of patience!

## 🧠 What I'm Learning
Building this has been an incredible deep dive into low-level engineering. Some key takeaways so far:
1. **Datasheet Reading:** Understanding pinouts and active-low/active-high signals.
2. **Computer Architecture:** Physically seeing how data moves from a register, through an ALU, and onto a common bus.
