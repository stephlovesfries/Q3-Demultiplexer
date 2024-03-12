# Q3-Demultiplexer
## Module 
To make a Verilog Demultiplexer, I used case statements to assign the values to the for outputs: W, X, Y,and Z, for every SEL input. At each SEL input, one of the outputs will be equal to A while the rest are 0.   
The truth table is as follows: 
| SEL | Output W | Output X | Output Y | Output Z|
| --- | --- | --- | --- | --- |
| 2'b00 | A | 2'b00 | 2'b00 | 2'b00|
| 2'b01 | 2'b00 | A | 2'b00 | 2'b00 |
| 2'b10 | 2'b00 | 2'b00 | A | 2'b00 |
| 2'b11 | 2'b00 | 2'b00 | 2'b00 | A |
  
![photo1710204938](https://github.com/stephlovesfries/Q3-Demultiplexer/assets/115708694/b29b8af7-76ef-4fd2-9e79-0f564730eca5)

## Testbench & Simulation 
Values were assigned to A and SEL to check demultiplexer function.
![photo1710204938 (1)](https://github.com/stephlovesfries/Q3-Demultiplexer/assets/115708694/96af4f6f-ecf4-40d4-b459-23ac851fb5d3)
![photo1710204938 (2)](https://github.com/stephlovesfries/Q3-Demultiplexer/assets/115708694/61dbd34f-d68d-4052-ba84-1fc9aa21a127)
