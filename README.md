# Ex-12 : 4-BIT-RIPPLE-COUNTER


**DATE:**


**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/sanjevrm/4-BIT-RIPPLE-COUNTER/assets/155142423/01f35cfc-cc20-4038-838e-63db3ee927c0)


In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/sanjevrm/4-BIT-RIPPLE-COUNTER/assets/155142423/7e6c6b05-53de-433a-a880-10964b5fd642)


![image](https://github.com/sanjevrm/4-BIT-RIPPLE-COUNTER/assets/155142423/9bee2228-39f3-4eae-963f-24d98a5b81df)


**Procedure**

1.Code Overview: Understand the Verilog module ripple_counter, which includes clock (clk) and reset (rst) inputs, and a 4-bit output count. The counter increments on each positive clock edge unless reset is asserted, resetting the count to 0.

2.Simulation Preparation: Use a Verilog simulator (e.g., ModelSim) and write a testbench module to apply clock and reset signals while monitoring the counter output.

3.Testbench Implementation: Instantiate the ripple_counter module in the testbench, generate clock and reset signals, apply them to the counter module, and observe the count output.

4.Simulation Execution: Compile both the counter module and the testbench, simulate the design, and verify that the counter counts from 0 to 15 (binary 1111) and resets to 0 when the reset signal is activated.

5.Verification and Debugging: Analyze timing diagrams to ensure proper counter behavior, debug any encountered issues during simulation, and make necessary modifications to the design for optimal functionality.

### Program
```
Developed by: Sanjev R M
Register no:212223040186
```
![image](https://github.com/sanjevrm/4-BIT-RIPPLE-COUNTER/assets/155142423/21809761-2ba4-4ea3-a394-0192daf4dcd8)


**RTL LOGIC FOR 4 Bit Ripple Counter**
![image](https://github.com/sanjevrm/4-BIT-RIPPLE-COUNTER/assets/155142423/e7f270de-4952-4810-986c-39e182aad9f8)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![image](https://github.com/sanjevrm/4-BIT-RIPPLE-COUNTER/assets/155142423/57bc9187-3cb1-42d6-8fda-bb28c69336dd)


### RESULTS
Thus, program excueted successfully
