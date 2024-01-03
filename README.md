## Name:Thirukumaran
## Reg:212223050056

## Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder:
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder:
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
### Program:

### Half Adder:
![Screenshot 2024-01-03 145805](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/c189e90d-7b39-4ae3-8299-8159a181bb26)


### Full Adder:

![Screenshot 2024-01-03 145823](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/7e190d7a-99cc-45ed-ab7c-4164606f035d)


Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
## Logic symbol:

### Half Adder:

![Screenshot 2024-01-03 145840](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/df891b55-2ae1-4bf6-b11d-659682a81e17)


### Full Adder:

![Screenshot 2024-01-03 145848](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/86364535-da65-44ca-9aa7-32b071d84b97)


## Truthtable:

### Half Adder:
![Screenshot 2024-01-03 145859](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/a538eaca-d3e7-4329-883a-db4634399fea)


### Full Adder:

![Screenshot 2024-01-03 145912](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/045c25af-5933-4e66-beda-afbeeab10f70)


### TIMING DIAGRAM

### Half Adder:

![Screenshot 2024-01-03 145928](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/371243bb-129c-4007-8a06-b6be12eec9c3)

### Full Adder:

![Screenshot 2024-01-03 145943](https://github.com/23010217/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154016053/669a6fe7-fe31-476f-ade3-b5cd3513db33)

### Result:

To design a half adder and full adder circuit and verify its truth table in Quartus using Verilong programming.
