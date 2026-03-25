## Loops in Python: Palindrome Number Checker

##Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## Algorithm
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

##  Program
~~~
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
~~~
## Output
![438839151-7fbd429c-e171-4330-b93f-bd74b4f36075](https://github.com/user-attachments/assets/3a5e7a95-3903-41f7-9257-61b02aa75739)

## Result
Thus, the program has been successfully executed
