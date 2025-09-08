# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.
To create an **abstract class** named `TypeShape` with an **abstract method** area, and implement this method in four subclasses: `Rectangle`, `Square`, `Circle`, and `Triangle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use from abc import ABC, abstractmethod to define abstract classes and methods.

2. **Create Abstract Class `TypeShape`**:
   - Define an abstract method `area()` decorated with `@abstractmethod`.

3. **Create Subclass `Rectangle`:**
   - Define attributes length and breadth.

4. **Implement the area() method to calculate rectangle area.**
   - Create Subclass Circle:

5. **Define attribute radius.**
   - Implement the `area()` method to calculate circle area.

6. **Create Subclass Square:**
   - Define attribute length.

7. **Implement the area() method to calculate square area.**
   - Create Subclass Triangle:

8. **Define attributes base and height.**
   - Implement the `area()` method to calculate triangle area.

9. **Create Objects & Call Methods:**
   - Instantiate objects for each subclass.
   - Call their `area()` methods and print the results.
---

## 💻 Program
```
import math

from abc import ABC

class type_shape(ABC): 
    #@abstractmethod
    pass

class Rectangle(type_shape):

    length = 6
    breadth = 4
  
    def area(self):
        return self.length * self.breadth

class Circle(type_shape):
    
    radius = 7
  
    def area(self):
        return 3.14 * self.radius * self.radius

class Square(type_shape):
    
    length = 4
   
    def area(self):
        return self.length * self.length

class triangle:
    
    length = 5
    width = 4
    
    def area(self):
        return 0.5 * self.length * self.width

r = Rectangle() # object created for the class 'Rectangle'
c = Circle() # object created for the class 'Circle'
s = Square() # object created for the class 'Square'
t = triangle() # object created for the class 'triangle'

print("Area of a rectangle:", r.area()) # call to 'area' method defined inside the class.
print(f"Area of a circle: {c.area():.2f}") # call to 'area' method defined inside the class.
print("Area of a square:", s.area()) # call to 'area' method defined inside the class.
print("Area of a triangle:", t.area()) # call to 'area' method defined inside the class.
```
## Output
<img width="745" height="229" alt="image" src="https://github.com/user-attachments/assets/2c25bb1f-7dbd-4a64-9b1e-dd0d499c1a6d" />

## Result
The program successfully demonstrates the use of an abstract class TypeShape with an abstract method `area()`, which is implemented by the subclasses Rectangle, Circle, Square, and Triangle.
