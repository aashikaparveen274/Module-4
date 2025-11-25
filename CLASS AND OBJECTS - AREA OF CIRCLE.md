# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
import math
class saveetha:
    def __init__(self,area):
        area = 3.1416*(pow(r,2))
        self.area=area
        
    def slot(self):
        print("Area of circle:",round(self.area,2))
        
r = eval(input())
res = saveetha(r)
res.slot()




```

### OUTPUT
<img width="856" height="250" alt="image" src="https://github.com/user-attachments/assets/177778cb-73bd-4c0a-8b05-17ac03afde57" />

### RESULT
Thus, the Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain has been implemented and executed successfully.
