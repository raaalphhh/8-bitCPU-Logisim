```markdown
# 🧮 8-Bit CPU (Logisim Simulation)

### Course Project – Computer Architecture / Logic Design

This repository contains the **Logisim circuit implementation** of an **8-bit CPU**.  
The design visually demonstrates how basic CPU components interact — including registers, ALU, memory, and control logic — to execute simple instructions.

---

## 🧩 Overview

This project simulates the behavior of an **8-bit accumulator-based processor**, capable of performing arithmetic, logic, and control operations.  
It serves as a **visual educational model** to understand instruction execution at the logic level.

---

## 🧠 Core Components

| Component | Description |
|------------|-------------|
| **Program Counter (PC)** | Keeps track of instruction address |
| **Instruction Register (IR)** | Holds the current fetched instruction |
| **Accumulator (ACC)** | Stores intermediate and final computation results |
| **ALU** | Performs ADD, SUB, AND, OR, XOR, and NOT operations |
| **Control Unit** | Decodes opcodes and generates control signals |
| **Memory (RAM)** | Stores 8-bit instructions and data |

---

## 🧰 Features

- 8-bit wide data path  
- Modular design (ALU, Registers, Control Unit)  
- Instruction fetching and decoding cycle  
- Clock-controlled execution  
- Compatible with Logisim Evolution

---

## 🧾 File Structure

8bit-CPU-Logisim/
├── 8bitCPU.circ # Main Logisim circuit file
├── 8bitCPU.txt 
└── README.md

yaml
Copy code

---

## ⚙️ How to Use

1. Open **Logisim Evolution**
2. Load the circuit file `8bitCPU.circ`
3. Click the **Clock** to run the CPU cycle manually or enable automatic ticks
4. Observe data flow in the accumulator, memory, and control lines

---

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
