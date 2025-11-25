# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```

try:
    n = int(input())
    a = []
    for i in range(n):
        element = int(input())
        a.append(element)
    print(a)
    print(a[6])

except IndexError:
    print("6 is not accepted")

```

### OUTPUT
<img width="832" height="472" alt="image" src="https://github.com/user-attachments/assets/64be9157-005e-4f95-93b5-eb94cebbd120" />

### RESULT
Thus, the Python program to handle IndexError using exception handling has been implemented and executed successfully
