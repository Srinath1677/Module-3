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


# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

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
```python
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
![444225631-e27f5cec-b620-4059-91e2-43e30854305c](https://github.com/user-attachments/assets/03dd92ab-5ca5-452f-860b-f8399bac34b6)

## Result
Thus,the program has been executed successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```python
def palindrome(a):
    if a==a[::-1]:
        print(f"The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
     
string =input()
palindrome(string)
```

## Output
![447309474-e501abc5-880f-4cf8-b08b-567c496ab29a](https://github.com/user-attachments/assets/080eafef-bf37-4ba1-b347-3d322ca090be)

## Result
Thus,the program executed successfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
t=eval(input())
print('n' not in t)
print('8' in t)
```
## Output
![447309768-c54c83fb-88c3-4687-885d-a02c208918d8](https://github.com/user-attachments/assets/a1b86466-6a56-412c-885b-0e21745615ae)

## Result
Thus,the program executed successfully.
