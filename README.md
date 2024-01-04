# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:


##half adder


![exp 3 prg](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/e8a40fe6-5761-42c8-ad01-3576eb5fbe38)

##full adder

![exp 3 prg 2](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/a7f09e97-e7f6-465f-b6a3-09b173ad150c)

##RTL

![exp 3 rtkl 1](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/cbd09ea9-7d72-4151-97bd-9b2e7ac3aeb0)


![exp 3 rtl 2](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/b6b93810-b11b-4e06-817e-db305dd6f399)


##truth table


![tt3](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/5b5040f3-a11c-4239-96fc-a6822e946a3b)


![exp 3 tt2](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/8847c538-083c-4689-9125-289f06b32b7c)

##output

![exp 3 wvfrm1](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/c74e8448-8db9-417e-b5ee-98c225a7761d)


![exp 3 wwfrm2](https://github.com/Saarulakshmi/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155513241/7b949304-ef98-4270-a2b5-0ae4c3cf85b6)












/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: saaru laksmi
RegisterNumber:  23008458
*


### Result:
