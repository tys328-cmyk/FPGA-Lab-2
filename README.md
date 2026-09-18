# FPGA-Lab-2
Project Description

This project implements a 1-bit full adder in Verilog and uses it as a building block to construct two 4-bit adder architectures: a Ripple Carry Adder (RCA) and a Carry Look Ahead Adder (CLA). Each design takes two 4-bit inputs (A, B) and a carry-in (CI), and produces a 4-bit sum (SUM) and a carry-out (CO). The two adder architectures are implemented and compared based on FPGA resource utilization.

Simulation

1. Open the project in Vivado.
2. Add the 1-bit full adder module and the desired 4-bit adder module (Ripple Carry Adder or Carry Look Ahead Adder) as design sources.
3. Add the corresponding testbench as a simulation source.
4. Set the testbench as the simulation top module.
5. Run Behavioral Simulation.
6. Verify from the waveform that each combination of A, B, and CI produces the expected SUM and CO output.

FPGA Implementation

1. Select the Basys 3 as the target FPGA board.
2. Select one of the 4-bit adder implementations as the top module.
3. Add the Basys 3 constraints file and assign the A, B, and CI inputs to switches and the SUM output to the seven-segment display.
4. Run Synthesis.
5. Run Implementation.
6. Generate the Bitstream.
7. Connect and power the Basys 3.
8. Open Hardware Manager and program the FPGA with the generated bitstream.
9. Test different switch input combinations and verify that the seven-segment display matches the expected SUM output.
