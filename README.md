### NAME : HARSHITHA V
### REGISTER NO : 212223230074
### EXP 1 : Study of Logic Gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**EQUPMENTS REQUIRED:**

Software – Quartus prime 

**THEORY:**

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

**PROCEDURE:** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.






**PROGRAM:**



Program for logic gates and verify its truth table in quartus using Verilog programming
```
module experiment1(a,b,yand,yor,ynot,yxor,ynand,ynor,yxnor);
input a,b;
output yand, yor,ynot,yxor,ynand,ynor,yxnor;
assign yand = a & b;
or(yor,a,b);
not(ynot,a);
xor(yxor,a,b);
nand(ynand,a,b);
nor(ynor,a,b);
xnor(yxnor,a,b);
endmodule
```




 
**LOGIC SYMBOL & TRUTHTABLE:**
![logic gates (1)](https://github.com/user-attachments/assets/80a81eb6-f196-4a70-9966-0b1cd3fecec2)












**RTL REALIZATION OUTPUT:** 


![digital-ex1](https://github.com/user-attachments/assets/2fb34ed1-5137-4587-9a8a-dc7ebd8c19f1)








**RTL:**



![image](https://github.com/user-attachments/assets/7de8761a-87f9-4dbd-8126-ac032dd39078)








**RESULT:**


Thu, the basic logic gates are studied and the truth tables are verified.
