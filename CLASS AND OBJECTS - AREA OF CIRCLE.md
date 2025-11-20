# Exp.No:4A  
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
#REG NO: 212223020002
#NAME:  ANUSRI SRIDHAR

import math

class umbrella:
    def rain(self, r):
        area = math.pi * r ** 2
        print(f"Area of the circle: {area:.2f}")

r = float(input("Enter the radius of the circle: "))

u = umbrella()
u.rain(r)



```

### OUTPUT

<img width="856" height="250" alt="image" src="https://github.com/user-attachments/assets/b365797e-b12e-4400-af92-3e6ad7bc3014" />


### RESULT

Thus, the Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain has been implemented and executed successfully.

