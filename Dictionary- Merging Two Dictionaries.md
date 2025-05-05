## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
def merge(dict1, dict2):
    merged_dict = {**dict1, **dict2} 
    return merged_dict
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'d': 4, 'e': 5, 'b': 10}  
merged_result = merge(dict1, dict2)
print("Merged Dictionary:", merged_result)
```
## Output
![image](https://github.com/user-attachments/assets/d60699a0-f7b6-4bbf-a885-96677df7bd02)

## Result
he program was successfully executed and merged the two dictionaries. As expected, the value for the key 'b' from dict2 (which is 10) overwrote the value from dict1 (which was 2).
