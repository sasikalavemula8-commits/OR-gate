# OR Gate using Verilog

## Description

This project implements a simple 2-input OR gate using Verilog HDL.

An OR gate produces a HIGH (1) output when at least one of its inputs is HIGH (1).

## Logic Expression

Y = A OR B

In Verilog:

Y = A | B

## Truth Table

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

## Files

- `or_gate.v` - Verilog design code
- `or_gate_tb.v` - Verilog testbench
- `README.md` - Project documentat