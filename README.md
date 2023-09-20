# GCD
The greatest common divisor (GCD) of two numbers is the largest number that is a divisor of both numbers. The Euclidean algorithm is a simple and efficient algorithm for finding the GCD of two numbers.

To implement the Euclidean algorithm in hardware, we can use a control path and a data path. The control path is responsible for sequencing the steps of the algorithm, while the data path performs the arithmetic operations.

The following is a high-level overview of how to implement the Euclidean algorithm on a Nexys A7 FPGA board:
1. Design the control path and data path. The control path can be implemented using a finite state machine (FSM). The data path can be implemented using combinational circuits  and registers.
2. Implement the control path and data path in Verilog or VHDL.
3. Synthesize the Verilog or VHDL code to a bitstream.
4. Download the bitstream to the Nexys A7 FPGA board.
5. Connect the inputs and outputs of the GCD calculator to the switches and seven-segment displays on the Nexys A7 FPGA board.
