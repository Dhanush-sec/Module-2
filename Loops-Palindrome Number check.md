## Loops in Python: Palindrome Number Checker

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
```
import math
n = int(input())
for r in range(n):
    print((n-r-1)*" ",end="")
    for c in range(0,r+1):
        print(f"{math.comb(r,c)}",end=" ")
    print(" ")
```
## Output

<img width="1920" height="1020" alt="530346896-f23b99fc-ffb0-43bd-800c-1569b9c6833a" src="https://github.com/user-attachments/assets/cc9eabb0-61c4-4f15-8299-18cdd5a0db12" />

## Result

Thus, the program has been executed successfully.
