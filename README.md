# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
    
![image](https://github.com/user-attachments/assets/46bccb93-d83e-4fd8-abe2-51957b4a2b52)
  
![image](https://github.com/user-attachments/assets/77abe19c-a9cc-45ca-af77-af1f6877cced)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:T Isaac Raja RegisterNumber:*/ 24900178

![image](https://github.com/user-attachments/assets/7a88f700-590b-4442-b6a0-6ea912c4a0aa)

![image](https://github.com/user-attachments/assets/ab2ad692-0f45-484a-8c34-84adf381e887)



**RTL Schematic**

![image](https://github.com/user-attachments/assets/5429d3ed-b1f4-4e82-bff0-aef823c0dc32)

![image](https://github.com/user-attachments/assets/272b48d6-080c-4150-af08-f480c240b610)



**Output/TIMING Waveform**

![image](https://github.com/user-attachments/assets/39c8fbea-5969-44ec-8597-7592ed4b737f)

![image](https://github.com/user-attachments/assets/44ee2afe-edfe-456d-9f77-2f52c1e96b98)



**Result:**
Thus, a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using verilog programming.
