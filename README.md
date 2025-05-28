# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```python
n=[1,2,-8]
sum=0
for i in n:
    sum+=i
print(sum)
```
## Output
![447305024-09ce2f4c-0cff-4fb0-934c-072638a1e25b](https://github.com/user-attachments/assets/bba821f7-529e-47e4-bbbe-aac9c649374a)


## Result
Thus ,the program executed successfully


# Regex in Python: Filter Words Without the Letter 'e'

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
```python
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)

```
## Output
![448229588-b4024e74-3ac2-4215-96f9-d3d4500fc73e](https://github.com/user-attachments/assets/b6e226b3-61ea-4660-85e3-36763cb5fd15)

## Result
Thus,the program executed successfully
