# Day 43 – XOR Gate Using MUX

## Introduction

Today, I implemented an XOR Gate using:

- 2:1 MUX
- 4:1 MUX

The design was written in Verilog HDL and simulated using Xilinx Vivado.

## XOR Logic

The XOR output is:

Y = A ⊕ B

---

## 1. XOR Gate Using 2:1 MUX

### Design

I0 = A  
I1 = ~A  
S = B

### Design Code

📌 Paste the screenshot of your 2:1 MUX XOR design code here.

### Testbench

📌 Paste the screenshot of your 2:1 MUX XOR testbench here.

### Waveform

📌 Paste the screenshot of your 2:1 MUX XOR waveform here.

### Schematic

📌 Paste the screenshot of your 2:1 MUX XOR schematic here.

---

## 2. XOR Gate Using 4:1 MUX

### Design

I0 = 0  
I1 = 1  
I2 = 1  
I3 = 0  

S1 = A  
S0 = B

### Design Code

📌 Paste the screenshot of your 4:1 MUX XOR design code here.

### Testbench

📌 Paste the screenshot of your 4:1 MUX XOR testbench here.

### Waveform

📌 Paste the screenshot of your 4:1 MUX XOR waveform here.

### Schematic

📌 Paste the screenshot of your 4:1 MUX XOR schematic here.

---

## Verification

The XOR Gate was verified using:

- Verilog HDL
- Testbench
- Simulation
- Waveform
- RTL Schematic

## Observation

- XOR Gate was successfully implemented using 2:1 and 4:1 MUX.
- The output is HIGH when the two inputs are different.
- The waveform verified the expected XOR operation.

## Tools Used

- Verilog HDL
- Xilinx Vivado
- RTL Simulation

## Learning

This implementation helped me understand how a MUX can be used to implement logic gates.
