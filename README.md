# Digital Circuit 
![image](https://github.com/user-attachments/assets/fb8f9009-ea1a-4608-916b-d1e379f09488)


 ### Objective    
 To design simulate and document a digital circuit that implements the functionality of a two bit binary adder using basic digital logic gates.
 

### WHAT THE CIRCIUT DOES
The circuit takes two numbers with bits A0,A1,B0 and B1, and adds the numbers.This  design effectively  handles the sum of two 2-bit binary numbers while managing the carry bits between different stages of the addition process.

### TESTING PROCESS
We assigned the values 1,1,0 and 1, to  A0,B0,A1 and B1 respectively  and we expected  the  outcome to be 100. The outcome was 100 because our circuit on S0 had no light which represent a zero,S1 also had no light to show a zero, and C2 had a red light to show one ,thus this verified that our circuit was indeed working.

### How the circuit was built
First we computed the addition of 2 bit binary numbers of our choice , A0,B0,A1 and B1 and assigned the values as 1,1,0 and 1. This  addition clarified the following points 
1.Our first half adder would add A0 and B0 using the XOR gate   to give out the first sum  and the carry bit of  1 would from the AND gate .
2.For the second half  adder the first XOR gate would perform the addition of A1 and B1 . The second XOR gate would add the sum of A1 and B1 from the first XOR gate along with the carry from the fist half adder  . The OR gate would finally combined the carry bits from the first half adder and the second half adder. 

### GROUP MEMBERS
K.G.M    202201992
M.A.R    202201074
T.S      202201293
M.B.R    202201173
M.P.S    202201948
L.N      2022019
