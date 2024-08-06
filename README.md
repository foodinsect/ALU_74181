# ALU 74181 Design

This project includes two versions of the ALU 74181 design. The ALU 74181 is a bit-slice arithmetic logic unit (ALU) that is capable of performing a variety of arithmetic and logic operations on binary data. It was widely used in early microprocessors and minicomputers.

## Folder Structure

- `01_ALU_74181`
- `02_ALU_74181_comb`

## 01_ALU_74181

This version of the ALU 74181 design is based on the datasheet specifications. The output is determined by the inputs according to the functionality described in the datasheet.

### Key Features

- **Datasheet-Based Design**: This design strictly follows the functional description provided in the ALU 74181 datasheet.
- **Input-Output Mapping**: The mapping of inputs to outputs is implemented as specified in the datasheet.

### Files

- `alu_74181.v`: Verilog implementation of the ALU 74181 based on the datasheet.
- `tb_alu_74181.v`: Testbench for simulating and verifying the functionality of the ALU 74181.

## 02_ALU_74181_comb

This version of the ALU 74181 design is based on the combinational logic circuit diagram of the ALU 74181. The design implements the combinational logic to replicate the behavior of the ALU 74181.

### Key Features

- **Combinational Logic Design**: This design uses the combinational logic circuit diagram to replicate the ALU 74181 functionality.
- **Logic Gate Implementation**: The implementation details follow the circuit diagram with logic gates to achieve the desired operations.

### Files

- `alu_74181_comb.v`: Verilog implementation of the ALU 74181 based on the combinational logic circuit diagram.
- `tb_alu_74181_comb.v`: Testbench for simulating and verifying the functionality of the ALU 74181 combinational logic version.


---
