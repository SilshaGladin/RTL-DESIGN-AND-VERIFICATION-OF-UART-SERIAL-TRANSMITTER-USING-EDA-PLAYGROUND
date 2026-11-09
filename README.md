# RTL Design and Verification of UART Serial Transmitter Using EDA Playground

## 1. Project Overview
This project focuses on designing and verifying an 8-bit UART Serial Transmitter using SystemVerilog. It demonstrates the VLSI front-end design process, including RTL coding, FSM implementation, testbench development, simulation and waveform analysis using EDA Playground.

## 2. Objectives
- Understand UART asynchronous serial communication.
- Design an 8-bit serial transmitter using RTL coding.
- Implement FSM-based transmission control.
- Verify functional correctness using a self-checking testbench.
- Analyze simulation outputs and timing waveforms.

## 3. Design Architecture
The UART transmitter consists of:
- Baud Rate Generator
- Finite State Machine (FSM)
- Shift Register
- Transmission Control Logic

The transmission frame consists of one start bit (0), eight data bits transmitted LSB first, and one stop bit (1).

## 4. RTL Implementation
The transmitter is developed using SystemVerilog with configurable clock frequency and baud rate. The FSM controls the IDLE, START, DATA and STOP states to ensure proper serial data transmission.

## 5. Verification and Simulation
A self-checking testbench is developed to validate the transmitter functionality. Test patterns such as 8'hA5, 8'h3C and 8'hFF are used to verify data transmission.

EDA Playground is used for RTL simulation, while EPWave is used to analyze waveforms and verify timing, start/stop bits and serial data output.

## 6. Applications
- Microcontroller communication
- Embedded systems
- IoT devices
- FPGA-based communication systems
- Digital IC design

## 7. Future Scope
The design can be extended with UART receiver integration, parity checking, FIFO buffering, hardware flow control, APB/AXI-Lite interfaces and UVM-based verification.

## 8. Conclusion
The project successfully demonstrates the RTL design and functional verification of a UART serial transmitter. It provides practical exposure to SystemVerilog, digital design, simulation and verification techniques used in the VLSI industry.
