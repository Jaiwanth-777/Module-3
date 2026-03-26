# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
list=[1,2,-8]
total=sum(list)
print(total)
```
## Output
![443557684-7dd5176d-6d7c-4e92-b93b-7908a1e68f96](https://github.com/user-attachments/assets/7dcc58dc-b624-46a3-824c-b81edfcf4770)

## Result
Thus,the program has been executed successfully.

# Regex in Python: Filter Words Without the Letter 'e'
Name: mohammedibrahim


## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
l1=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items:
   if not re.search(r"e",i):
      l1.append(i)
print(l1)
```
## Output
![443558263-e20ae089-3c58-4d0d-8ee1-c93dadf94222](https://github.com/user-attachments/assets/d095faa0-1ddc-4d11-97b8-6674f7d400cd)

## Result
Thus,the program has been executed successfully.

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String
Name: mohammedibrahim


## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```

def remove(str):
  l=len(str)
a=""
n=int(input())
for i in range(0,l):
  if i==n:
    a=a+""
  else:
    a=a+str[i]
print(a)
```
## Output
![443559104-f1170fa2-e0e9-47fc-aeb4-9bc0fe79d627](https://github.com/user-attachments/assets/cc37ed40-343f-41e0-80b3-5b2c2d4bf667)

## Result
Thus,the program has been executed successfully.
