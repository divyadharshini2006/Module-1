# Experiment No: 1e – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.
2. Read the three numbers: num1, num2, and num3 from the user.
3. Compare num1, num2, and num3 to find the largest number:
If num1 is greater than or equal to both num2 and num3, then num1 is the maximum.
Else, if num2 is greater than or equal to both num1 and num3, then num2 is the maximum.
Otherwise, num3 is the maximum.
4. Print the maximum value along with the input numbers in the format:
"The maximum of num1, num2, num3 is max_num."
5. Terminate the program.

## PROGRAM
```python
a=int(input())
b=int(input())
c=int(input())
max=a if a>b and a>c else b if b>a and b>c else c
print(f'The maximum of {a}, {b}, {c} is {max}')
```
## OUTPUT
![Screenshot 2025-04-26 142537](https://github.com/user-attachments/assets/aa8645b1-f19a-4dee-af55-8feab10c227d)

## RESULT
Thus To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator) has been implemented successfully.
