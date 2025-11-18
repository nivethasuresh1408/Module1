# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```python

a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))
x = complex(a, b)

print("Complex number:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
```
## Output
![438639571-778828b7-6c2b-4a39-9984-6b60a54eb980](https://github.com/user-attachments/assets/31586238-a956-469b-814c-f368cf28d8e2)

## Result
```
The program successfully creates a complex number using two integer inputs
and displays the number along with its real and imaginary parts.
