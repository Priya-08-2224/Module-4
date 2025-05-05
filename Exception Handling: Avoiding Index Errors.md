# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40, 50]
try:
    print(list1[5])  
except IndexError:
    print("You're out of list range")

```
## Output
![image](https://github.com/user-attachments/assets/623e308a-8ffe-4e59-b25a-782a43c3474e)

## Result
The program was successfully executed. When trying to access an index that is out of range (index 5), the IndexError was caught by the except block, and the custom message "You're out of list range" was displayed as expected.
