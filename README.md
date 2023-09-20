# RTL-Day-2-Adder-Subtractor

## Problem Statement: Implementing Adders and Subtractors
## Theory: 
1. Half Adder: Half Adder is a combinational logic circuit which is designed by connecting one EX-OR gate and one AND gate. The half adder circuit has two inputs: A and B, which add two input digits and generates a carry and a sum. The output obtained from the EX-OR gate is the sum of the two numbers while that obtained by AND gate is the carry. There will be no forwarding of carry addition because there is no logic gate to process that. Thus, this is called the Half Adder circuit.

 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/cb48f4f1-298a-4011-b13f-ba6403cf0338)
### Fig: Half Adder Truth Table

2. Full Adder: Full Adder is the circuit that consists of two EX-OR gates, two AND gates, and one OR gate. Full Adder is the adder that adds three inputs and produces two outputs which consist of two EX-OR gates, two AND gates, and one OR gate. The first two inputs are A and B and the third input is an input carry as C-IN. The output carry is designated as C-OUT and the normal output is designated as S which is SUM.

 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/0804ffcb-ef53-4273-869c-7d0beaa74b62)
### Fig: Full Adder Truth Table

3. Half subtractor: A half subtractor is a digital logic circuit that performs binary subtraction of two single-bit binary numbers. It has two inputs, A and B, and two outputs, DIFFERENCE and BORROW. The DIFFERENCE output is the difference between the two input bits, while the BORROW output indicates whether borrowing was necessary during the subtraction. The half subtractor can be implemented using basic gates such as XOR and NOT gates. The DIFFERENCE output is the XOR of the two inputs A and B, while the BORROW output is the NOT of input A and the AND of inputs A and B.

 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/18689091-1bb5-48ed-bcbb-9dca2b325049)
### Fig: Half Subtractor Truth Table

4. Full subtractor: A full subtractor is a combinational circuit that performs subtraction of two bits, one is minuend and other is subtrahend, taking into account borrow of the previous adjacent lower minuend bit. This circuit has three inputs and two outputs. The three inputs A, B and Bin, denote the minuend, subtrahend, and previous borrow, respectively. The two outputs, D and Bout represent the difference and output borrow, respectively.
 
 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/b90abc0f-0929-427a-bb16-e8ba817479d7)
### Fig: Full Subtractor Truth Table 


## 1.	Half-Adder

### Simulation Output:
 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/93a6926a-2337-4e82-9924-4a7657f4e09f)

### Schematic:  
![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/d6b77b2f-c34d-4f9d-b17e-be64fa6ac299)


 
## 2.	Full-Adder
### Simulation Output:
![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/7af645f0-a29f-4044-a164-fbd2b4dd0549)

### Schematic: 
![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/81a344a8-b98a-4398-952d-d729c4def7f8)


## 3.	Half-Subtractor

### Simulation Output:
 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/563567e2-b5bf-4b7c-a660-295aa278758f)

### Schematic:  
 ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/a107245b-84b5-4306-b392-1a8b72e23369)


## 4.	Full-Subtractor

### Simulation Output:
![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/d7bdd031-751b-4e18-8109-915b3f4b4dc4)

### Schematic:  
  ![image](https://github.com/tusharshenoy/RTL-Day-2-Adder-Subtractor/assets/107348474/e12be9ff-0171-4cb1-ab73-65c832dae6e4)

## References
#### [Reference 1 Half and Full Adder](https://www.geeksforgeeks.org/difference-between-half-adder-and-full-adder/)
#### [Reference 2 Half-Subtractor](https://www.geeksforgeeks.org/half-subtractor-in-digital-logic/)
#### [Reference 3 Full-Subtractor](https://www.geeksforgeeks.org/full-subtractor-in-digital-logic/)

