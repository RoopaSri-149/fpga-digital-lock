The FPGA Digital Lock is a secure password-based electronic locking system designed and implemented using Verilog HDL on an FPGA development board. The project demonstrates how digital logic can be used to create a basic access-control system without requiring a conventional microcontroller.

The system allows the user to enter a predefined password through input switches/buttons. The entered password is compared with the stored password using digital logic. If the entered password matches the correct password, the system grants access by activating an unlock/valid indication. If the password is incorrect, the system generates a wrong-password indication and prevents access.

The complete design is developed using Verilog HDL and synthesized, simulated, and implemented using AMD Xilinx Vivado. The project demonstrates important FPGA concepts such as combinational logic, sequential logic, registers, counters, state-based control, input handling, and output control.
