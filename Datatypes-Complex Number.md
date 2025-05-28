#  Datatypes-Complex Number Creation in Python

##  Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

##  Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

##  Program

``` python


real = float(input())
imag = float(input())

complex_num = complex(real, imag)

print(complex_num)
print(complex_num.real)
print(complex_num.imag)

```

## Output

![image](https://github.com/user-attachments/assets/07ae571d-6012-443c-9385-ea46f31fedd1)

## Result

Thus, the program has been successfully executed.
