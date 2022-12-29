# 4-bit-alu
This is the verilog code for a 4bit arithmetic and logic unit which can do 8 operations
//modules are implemented in gate level format

it basically have 2 4bit input and a 3bit operation select line

when the operation select line is
                                 000           addition
                                 001           subtraction
                                 010           Logical AND
                                 011           Logical XOR
                                 100           Logical OR
                                 101           left shift
                                 110           right shift
                                 111           multiplication
                                 
gate level implementation each module is made and connected to a 8:1 mux
4 bit inputs are given common to all blocks and operation select line to mux select 
