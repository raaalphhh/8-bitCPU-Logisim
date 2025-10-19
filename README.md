# 🧮 8-Bit CPU (Logisim Simulation)

This repository contains the **Logisim circuit implementation** of an **8-bit CPU**. The design demonstrates how core CPU components — including the **ALU**, **registers**, **control unit**, and **memory** — interact to execute basic instructions at the logic level.

---

## 🧩 Project Overview

This simulation models an **8-bit accumulator-based processor**, capable of performing **arithmetic, logic, and control operations**. It serves as a **visual learning tool** to understand the internal workings of a CPU, such as instruction fetching, decoding, and execution cycles.

---

## 🧠 Core Components

| Component | Description |
|------------|-------------|
| **Program Counter (PC)** | Tracks the address of the next instruction |
| **Instruction Register (IR)** | Stores the currently fetched instruction |
| **Accumulator (ACC)** | Holds intermediate and final results |
| **Arithmetic Logic Unit (ALU)** | Executes arithmetic and logic operations (ADD, SUB, AND, OR, XOR, NOT) |
| **Control Unit** | Decodes opcodes and generates control signals |
| **Memory (RAM)** | 8-bit instruction and data storage |

---

## ⚙️ Features

- 🧮 8-bit data width  
- 🧱 Modular circuit design (ALU, Registers, Control Unit)  
- 🔄 Instruction fetch-decode-execute cycle  
- ⏱️ Clock-controlled operation  
- 🧩 Fully compatible with **Logisim Evolution**

---

## 📁 File Structure

```plaintext
8-bitCPU-Logisim/
├── 8-bitCPU.circ          # Main Logisim circuit file
├── 8-bitCPU-Logisim.txt   # Design documentation / backup
└── README.md

🚀 How to Run the Simulation

Open Logisim Evolution
Load the circuit file 8-bitCPU.circ
Click the Clock icon to advance cycles manually or enable Automatic Ticks to observe continuous execution
Watch the flow of data through the CPU components (ACC, ALU, PC, etc.)

### 👨‍💻 Developers
```
Developed by Group Members – Computer Engineering Students
ARMADO, James Neftali B.
ANDAL, Anthony Aries C.
BINOSA, Joyce C.
BUENAVENTURA, Ralph D.
CAPARAS, Mumphry S.
CARASIG, Janelle Isabel M.
CASTRO, Ia Micah G.
CERRO, Christian Paul
CORREA, Reingel F.
DELA CRUZ, Jay Vee A.
ERFE, Irysse J.
LORENZO, Yesuah Jirah D.

📍 Bulacan State University | Computer Architecture and Organization - Course Project 
🧾 Academic Term: 1st Semester, AY 2024–2025
```
