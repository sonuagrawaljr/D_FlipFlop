# Implementation of D-Flip Flop Using 28nm CMOS Technology
The D flip flop is designed using 28nm CMOS technology by using Synopsys Custom Compiler


# Table of Content 
- ABSTRACT 
- INTRODUCTION
- TOOLS USED
- D FLIP FLOP CIRCUIT DESIGN
- CMOS NAND GATE
- CMOS INVERTER
- CMOS D FLIP FLOP
- STIMULATION 
- NETLIST
- ACKNOWLEDGEMENT 
- REFERENCE 


## ABSTRACT

Flip Flops are basic building blocks of digital electronic circuits used in communications, Computers, and many circuits and have stable states that store binary data. The stored data can be changed by applying varying inputs. In this paper, the D flip flop is designed using 28nm CMOS technology by using Synopsys Custom Compiler.

# INTRODUCTION

A D (or Delay) Flip Flop shown in Figure 1(a) is a digital electronic circuit used to delay the change of state of its output signal (Q) until the next rising edge of a clock timing input signal occurs. Flip Flop is a sequential circuit, which is used to store a single bit of information. Flip-Flop is an edgetriggered sequential block. The major applications of D flipflop are to introduce delay in timing circuit, as a buffer, sampling data at specific intervals.

When the D input is provided to the Flip Flop, the circuit check for the clock signal is the signal of the clock is high (for level triggered d flip-flop) then with every clock pulse, the input D propagates to the output Q. For edge-triggered flipflop, the circuit check for the transition of clock pulse according to which the flip Flop propagates the input to the output; edge-triggered can be positive edge-triggered or negative triggered. Positive edge-triggered D flip-flop changes its output according to input with every transition of the clock pulse from 0 to 1. As for the negative edge-triggered D, flip-flop changes its output according to input with every transition of the clock pulse from 1 to 0.
