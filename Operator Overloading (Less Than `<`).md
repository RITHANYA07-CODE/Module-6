# 🐍 Python OOP: Operator Overloading (Greater Than `>`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **greater than (`>`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
# Program to demonstrate operator overloading using ">" operator

class A:
    def __init__(self, a):
        self.a = a

    # Overloading the greater than operator
    def __gt__(self, other):
        if self.a > other.a:
            return "ob1 is greater than ob2"
        else:
            return "ob2 is greater than ob1"


# Create objects
ob1 = A(10)
ob2 = A(20)

# Use ">" operator
print(ob1 > ob2)

```
## Output
<img width="635" height="153" alt="image" src="https://github.com/user-attachments/assets/84dc79e2-446d-4701-bacd-23967aa20d79" />

## Result
Thus, the Python program to demonstrate operator overloading using the greater than `(>)` operator was successfully implemented and executed. The output verified that the overloaded operator works as intended.
