# Module 2

## Name: Dharshini S
## Reg no: 212224040074

# 1. Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **10** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `10` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

```
x=int(input())
y=bin(x)
print(y)
```
## Output
<img width="1132" height="218" alt="image" src="https://github.com/user-attachments/assets/1c3f19e2-b4c5-4f59-9d02-acce0521fae2" />


## Result
Thus ,the program is executed successfully.

---

# 2. Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
a=int(input())
b=int(input())
def result(a,b):
    d=a%b
    print('modulo is',d)
```
## Output
<img width="1099" height="262" alt="image" src="https://github.com/user-attachments/assets/de4eae56-7cb6-48c5-a507-4881ec0ee28f" />


## Result
Thus,the program is executed suucessfully.

---

# 3. Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))
```
## Output
![Screenshot (136)](https://github.com/user-attachments/assets/3826ebf1-9fe2-439b-b648-94fe609756f9)

## Result
Thus,the program is executed successfully.

---

# 4. 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.



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
```
rows = int(input())
for i in range(1, rows + 1):
    for j in range(1, i + 1):
        print(j, end=" ")
    print()
```

## Output
<img width="1126" height="524" alt="image" src="https://github.com/user-attachments/assets/4945873e-3a50-4a74-abbe-74c8abe42ae9" />


## Result
Thus,the program is executed successfully.

---

## 5. Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```python
num=int(input()) 
rev=0 
temp=num 
while temp>0: 
rev=(10*rev)+temp%10 
temp//=10 
if rev==num: 
print("The given number {} is a Palindrome".format(num)) 
else: 
print("The given number {} is not a palindrome".format(num))
```
## Output
![Screenshot (138)](https://github.com/user-attachments/assets/ac185760-5341-47e4-9e70-38f4b7dda936)


## Result
Thus,the program as been executed successfully.
