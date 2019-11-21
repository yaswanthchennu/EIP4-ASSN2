# EIP4-ASSN2
strategy: 
1)Without directly converting the last step which is from 4x4 to 1x1(2560 parameters).
I have convolved the 4x4 to 2x2 and then 1x1(by which i can reduce the number of parameters)(1860 parameters).
2)As the dropout is not used in the last iteration.We have removed from the code. ACCURACY-99.4% PARAMETERS-15670
