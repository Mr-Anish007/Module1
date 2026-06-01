# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program

```
a=int(input())
if(a%2==0):
    print("EVEN")
else:
    print("ODD")
```
## Output

<img width="1169" height="290" alt="image" src="https://github.com/user-attachments/assets/8b44e32b-6d1c-4ba2-9c14-b9b343019ccf" />

## Result

The program displays "EVEN" if the entered number is divisible by 2; otherwise, it displays "ODD".
