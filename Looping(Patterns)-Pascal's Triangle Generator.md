# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
# Program to generate Pascal's Triangle
```
import math
rows = int(input())
for i in range(rows):
    print(" " * (rows - i), end="")
    for j in range(i + 1):
        value = math.comb(i, j) 
        print(value, end=" ")
    print()
```
## Sample Output
<img width="517" height="306" alt="Screenshot 2025-10-20 123043" src="https://github.com/user-attachments/assets/81695c96-bfd0-4eb7-a521-346f1676022b" />

## Result
Thus, to write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user is executed successfully.
