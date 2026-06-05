## Built-in Functions -Binary Conversion Using Built-in Functions in Python
## Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## Algorithm
Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.
## Program
Add Code Here
```
a = 16
print(bin(a))
```
## Output
<img width="1043" height="246" alt="image" src="https://github.com/user-attachments/assets/1c43ffe0-0114-4a8a-ae37-9b16210fbf7a" />
## Result
The program successfully converts the number 16 into its binary representation and displays the result as 0b10000 on the screen.

Functions in Python: Modulo Calculator
## Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## Algorithm
Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.
## Program
```
def result(a,b):
   return a%b
a=int(input())
b=int(input())
modulo=result(a,b)
print("modulo is",modulo)
```
## output
<img width="1047" height="241" alt="image" src="https://github.com/user-attachments/assets/2dd7c88e-2891-434b-8537-83139a3dd5b7" />
## Result
The program successfully defines a function and returns the modulo of the two inputs

Lambda Function in Python: Addition of Two Numbers
## Aim
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## Algorithm
Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.
## Program
```
a=int(input())
b=int(input())
f=lambda a,b:a+b
c=f(a,b)
print(c)
```
## output
<img width="606" height="287" alt="image" src="https://github.com/user-attachments/assets/c97ed73e-1627-45a5-8f62-96384ae6a26e" />
## Result
The program successfully created lambda function to find the sum

🔺 Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## Aim
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## Algorithm
Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.
## Program
```
def pascal_triangle(n):
    for i in range(n):
        print(" "*(n-i-1),end="")
        val=1
        for j in range(i+1):
            print(val,end=" ")
            val=val*(i-j)//(j+1)
        print()
n=int(input())
pascal_triangle(n)
```
## sample output
<img width="1052" height="536" alt="image" src="https://github.com/user-attachments/assets/36795907-5f6e-4d08-8a30-54aa8e528cd8" />
## Result
The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.

Loops in Python: Palindrome Number Checker
## Aim
To write a Python program that checks whether a given number is a palindrome using loops.

## Algorithm
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
## Program
```
n=int(input())
rev=0
org=n
while n>0:
    rem=n%10
    rev=rev*10+rem
    n//=10
if(rev==org):
  print("The given number",org,"is a Palindrome")
else:
    print("The given number",org,"is not a palindrome")
```
<img width="1053" height="197" alt="image" src="https://github.com/user-attachments/assets/aca18ab3-e450-48b3-9d35-c3f840028f20" />

##  Result
The program successfully takes a number as input from the user, reverses it using a while loop, and compares it with the original number. If both are equal, it confirms that the number is a palindrome; otherwise, it displays that it is not a palindrome.
