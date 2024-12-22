### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
 ```
 module exp1(a,b,f1,f2,f3,f4,f5,f6,f7);
 input a,b;
 output f1,f2,f3,f4,f5,f6,f7;
 assign f1=a&b;
 assign f2=a|b;
 assign f3=~a;
 assign f4=~f1;
 assign f5=~f2;
 assign f6=a^b;
 assign f7=~(a^b);
 endmodule

```

 Developed by: RegisterNumber: OBELESH R (24901123)
 
**Logic symbol & Truthtable**
![Screenshot 2024-12-22 153446](https://github.com/user-attachments/assets/0ca7cae5-e7e6-4c40-a020-797d2e5e7728)
![Screenshot 2024-12-22 153455](https://github.com/user-attachments/assets/502e7e9c-f59b-403d-83ca-d8c3d5169472)


**RTL realization Output:** 
![Screenshot 2024-12-22 153504](https://github.com/user-attachments/assets/5134bf6e-8700-455f-a79e-0e203f2c7a1a)

**RTL**
![Screenshot 2024-12-22 153518](https://github.com/user-attachments/assets/69ffe91f-c557-4458-a5e9-75d1203754f5)

**Result:**


