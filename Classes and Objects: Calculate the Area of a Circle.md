# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math

class cse:
    def mech(self, r):
        area = math.pi * r ** 2
        print(area)

radius = float(input())
obj = cse()
obj.mech(radius)
```

## Output
![image](https://github.com/user-attachments/assets/9e7afba5-e52b-4220-9265-f1635c0d71a8)


## Result
The Python program defining a class cse with a method to calculate the area of a circle has been executed successfully, and the output has been verified.
