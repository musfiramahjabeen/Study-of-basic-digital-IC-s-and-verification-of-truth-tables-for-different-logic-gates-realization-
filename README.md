# Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-
## Aim:
#### To study about the different digital IC’s and to verify the truth table in Quartus for the basic logic gates using Verilog programming.

## Equipments Required:
#### Hardware – PCs, Cyclone II , USB flasher
#### Software – Quartus prime
## Theory:
### Introduction -
#### Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

#### AND gate
#### OR gate
#### NOT gate
#### NAND gate
#### NOR gate
#### Ex-OR gate
#### Ex-NOR gate

### 1) AND gate
The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB

Y= A.B

### 2) OR gate
The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.

Y= A+B

### 3) NOT gate
The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.

Y= A'

### 4) NAND gate
This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.

Y= (AB)’

### 5) NOR gate
This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.

Y= (A+B)’

### 6) Ex-OR gate
The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.

Y= A⊕B

### 7) Ex-NOR gate
The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.

Y= A⊕B

## Procedure:
#### (i)   Connect the supply (+5V) to the circuit.

#### (ii)  Switch ON the main switch.

#### (iii) Press the switches for inputs “A” and “B”. The switch is ON state when 1 is pressed. The switch is OFF state when 0 is pressed.

#### (iv)  If the output is 1, then the bulb glows.

#### (v)   Check all the gates following the same procedure.

## Program:

#### Program to verify the truth table in quartus for the basic logic gates using Verilog programming.
#### Developed by: MUSFIRA MAHJABEEN
#### RegisterNumber:  23002165

```
module ex01(A,B,Y1,Y2,Y3,Y4,Y5,Y6,Y7);
input A,B;
output Y1,Y2,Y3,Y4,Y5,Y6,Y7;
and (Y1,A,B);
or (Y2,A,B);
not (Y3,A);
xor (Y4,A,B);
xnor (Y5,A,B);
nand (Y6,A,B);
nor (Y7,A,B);
endmodule
```
## Output:
### Logic symbol & Truthtable:
#### 1.AND gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/a3288426-4bcc-4e3f-bf14-1bc41c6650e5)
#### 2.OR gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/a07c7e18-3526-461d-85e9-94a21bf7aab3)
#### 3.NOT gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/1c416d1d-2c4a-45df-814e-d3ea5ac50017)
#### 4.NAND gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/6ae1e82c-2267-4b66-ad30-d6e26ce57040)
#### 5.NOR gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/12fb19c8-5ca1-4ba6-b0b6-ae07eb7355fd)
#### 6.EX-OR gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/995a3496-131b-46d5-ab72-ef68689aa122)
#### 7.EX-NOR gate
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/124c7887-0656-42ee-8132-bc0213136432)

### RTL realization:
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/5e3e3cd3-9aa4-49c8-9481-e18b46b83254)
### WaveForm:
![image](https://github.com/SaravananPV3010/Study-of-basic-digital-IC-s-and-verification-of-truth-tables-for-different-logic-gates-realization-/assets/139754526/a79899fa-0819-4cda-871c-30d3ca0d02f5)




## Result:
#### Thus the different digital IC’s are studied and the truth table for different logic gates are verified.

