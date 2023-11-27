# Experiment--04-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.

## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: DURGA U 

RegisterNumber: 23003210

### HALF SUBTRACTOR:

![Exp4 hs code](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/c2e8aeae-9a5a-4230-b8d0-efd44733b112)


### FULL SUBTRACTOR:

![Exp4 fs code](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/5e476209-2f43-4ba5-a4d0-6feb8eafe024)




## RTL:
### HALF SUBTRACTOR:

![Exp4 hs RTL diagram](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/f16e6007-dd8b-4ec1-9557-5570fdfc6c4f)


### FULL SUBTRACTOR:

![Exp4 fs RTL diagram](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/1f920b60-56c5-4e80-9461-5ffba9cb0063)

## Truthtable:
### HALF SUBTRACTOR:

![Exp4 truthtable hs](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/63b5a9e4-bd59-4b2e-9aeb-66b460048d1e)

### FULL SUBTRACTOR:

![Exp4 truthtable fs](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/25618f7c-5326-4da2-8b8d-e4c20a0b007e)

## Timing diagram :
### HALF SUBTRACTOR:

![hs wave](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/d0287e87-fd11-4460-9b0a-f91d945e8821)

### FULL SUBTRACTOR:

![fs wave](https://github.com/DurgaUmapathy/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152186191/6fad68c3-8810-4429-8ca7-5c6e50a4b6d6)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
