Exp.No:2e
SEB - COMPUTING POWER
AIM

To write a Python program to compute the power of a given number using an appropriate built-in function.
ALGORITHM

    Begin the program.
    Input the base number (base) from the user.
    Input the exponent number (exp) from the user.
    Use the built-in pow() function to compute the base raised to the power of the exponent.
    Print the result using the print() function, displaying the power in a formatted output.
    Terminate the program.

PROGRAM


num = int(input())
sum = 0
for i in range(1, num + 1):
    if i % 2 != 0:
        sum += i

print(f"The sum of the series = {sum}")

OUTPUT

image
RESULT

Thus the program to calculate the sum of the odd number series from 1 to N using a loop has been implemented and executed successfully.
