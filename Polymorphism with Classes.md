# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
class Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")


class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")


# Generic function to demonstrate polymorphism
def func(obj):
    obj.type()
    obj.color()


# Create objects
b = Beans()
m = Mango()

# Call the generic function with different objects
print("Details of Beans:")
func(b)

print("\nDetails of Mango:")
func(m)

```
## Output
<img width="410" height="214" alt="image" src="https://github.com/user-attachments/assets/139c5e71-5ece-44f1-9310-b40029b007e7" />

## Result
Thus, the Python program to demonstrate polymorphism with classes using the `Beans` and `Mango` classes was successfully implemented and executed. The output confirmed that a single generic function can work with different objects to display their type and color, validating the concept of polymorphism.
