# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**


**4 Bit Ripple Counter**


A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.


![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)


In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.


![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)


![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)




**Procedure**

1. Understand the verilog module ripple counter.


2. Use a verilog simulator and write a testbench module to apply clock.


3. Generate clock and reset signal, apply them to the counter module and observe count output.


4. Compile both the counter module and testbench,simulate the design and verify that the counter counts from 0-15


5. Analyse the timing diagram to ensure proper counter behavior.


**PROGRAM**


Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.


**Developed by: JAYAGANAPATHI S**


**RegisterNumber:24900059**


![Screenshot 2024-12-11 140334](https://github.com/user-attachments/assets/e50b9a27-3af6-45a7-885c-476646065763)


**RTL LOGIC FOR 4 Bit Ripple Counter**


![330457800-f894ec00-35ff-42aa-91d4-33a3c4f83828](https://github.com/user-attachments/assets/96d4032f-702e-44f9-9526-eb40ba0aaa68)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**


![330457234-bf1e161f-d49e-4f1c-91d4-bed3185e20cf](https://github.com/user-attachments/assets/c8669494-e50a-41cc-862c-35bad908674e)


**RESULTS**


Thus implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is done successfully.
