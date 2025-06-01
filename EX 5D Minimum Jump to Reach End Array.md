# EX 5D Minimum Jump to Reach End Array
## DATE:14/5/25
## AIM:
To write a python program for finding the minimum number of jumps needed to reach end of the array using Dynamic Programming.


## Algorithm
1.Create a jumps[] array.

2.Initialize an array jumps[] where each element is set to a large number (inf), except for the first element, which is set to 0. This represents the minimum number of jumps needed to reach each index.

3.Start iterating through the array.

4.Loop through each element of the array (starting from index 1).

5.For each element arr[i], check if it's possible to reach index i from any earlier index j (i.e., i <= j + arr[j]).

6.If reachable, update jumps[i] to be the minimum of its current value and jumps[j] + 1.

7.The value in jumps[n-1] will give the minimum jumps required to reach the end.

8.If it is still inf, return -1 because it's not possible to reach the end. 

## Program:
```
/*
To implement the program to finding the minimum number of jumps needed to reach end of the array.


Developed by: Keziah.F
Register Number: 212223040094 
*/
```

## Output:

![image](https://github.com/user-attachments/assets/65a4aee2-299b-4549-8aac-c995557a1ef0)



## Result:
Thus the program was executed successfully for finding the minimum number of jumps to reach end.
