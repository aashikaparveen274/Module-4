# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
#Add Your Code Here
def character_frequency(s):
    frequency = {}
    for char in s:
        if char in frequency:
            frequency[char] += 1
        else:
            frequency[char] = 1
    return frequency
user_input = input()
result = character_frequency(user_input)
print(result)



```

### OUTPUT

<img width="1337" height="225" alt="image" src="https://github.com/user-attachments/assets/32b4c0b5-315d-407e-93a2-5d92d932cd38" />

### RESULT
Thus, the Python program to create a dictionary of character frequencies from a string has been implemented and executed successfully.
