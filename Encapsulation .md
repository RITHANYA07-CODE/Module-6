# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length        # Private attribute
        self.__breadth = breadth      # Private attribute

    def display(self):
        print(f"Length: {self.__length}")
        print(f"Breadth: {self.__breadth}")

# Instantiate the Rectangle object
rect = Rectangle(10, 5)

# Display the values
rect.display()

```
## Output
<img width="508" height="176" alt="image" src="https://github.com/user-attachments/assets/6c8c74c4-9081-430e-9e16-e0976a3cbcd2" />

## Result
The program successfully demonstrates encapsulation in Python by using private member variables `__length` and `__breadth` within the Rectangle class.
