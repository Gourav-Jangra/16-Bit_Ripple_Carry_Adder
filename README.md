# 16-Bit_Ripple_Carry_Adder
The aim is to write a code for 16 bit full adder which is in ripple carry architecture, along with this there are status flags are also given. The coding is needed to be done in gate level description.

Verilog is used as hardware description language and xlinix Vivado 2017.1 is used for implementation. Module instantiation of lower level is used to go to higher level.

Generation of status flags:
- Sign - whether sum is positive or negative
- Zero - whether sum is zero or not
- Carry - whether there is carry out of the last stage
- Parity - whether no. oof 1's is odd or even
- Overflow - whether the sum can't fit in 16 bits

![RTL Design of 16 Bit Adder](https://imgur.com/EFvJzXt.png)

Figure 1 : Schematic of a full adder using gates

![RTL Design of 16 Bit Adder](https://imgur.com/A8ZObEn.png)

Figure 2 : Schematic of a 4 bit rippple carry adder using 1 Bit Full Adder

![RTL Design of 16 Bit Adder](https://imgur.com/7B7YTWG.png)

Figure 3 : Schematic of a 16 bit rippple carry adder using 4 Bit ripple carry Adder and status flags



 
