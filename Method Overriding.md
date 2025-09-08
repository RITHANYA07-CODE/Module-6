# 🐦 Method Overriding – Bird, Sparrow, and Ostrich Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Bird` with a method `flight`, and two child classes `Sparrow` and `Ostrich` that override the `flight` method. 

## 📋 ALGORITHM:

1. Define the `Bird` class with a method named `flight()` that prints `"There are many types of birds."`.
2. Define the `Sparrow` class as a subclass of `Bird`, and override the `flight()` method to print `"Sparrows can fly."`.
3. Define the `Ostrich` class as a subclass of `Bird`, and override the `flight()` method to print `"Ostriches cannot fly."`.
4. Create an instance of the `Bird` class named `obj_bird`.
5. Create an instance of the `Sparrow` class named `obj_sparrow`.
6. Create an instance of the `Ostrich` class named `obj_ostrich`.
7. Use a `for` loop to iterate over all three objects.
8. Within the loop, call the `flight()` method using the loop variable.
9. Output will demonstrate method overriding: printing different flying behaviors for each bird.

---

## 💻 PROGRAM:
```
class Bird:
    def intro(self):
        print("There are many types of birds.")
	
    def flight(self):
        print("Most of the birds can fly but some cannot.")

class sparrow(Bird):
    def flight(self):
        print("Sparrows can fly.")
	
class ostrich(Bird):
    def flight(self):
        print("Ostriches cannot fly.")
	
obj_bird = Bird()
obj_bird.intro()
obj_bird.flight()

obj_spr = sparrow()
obj_spr.intro()
obj_spr.flight()

obj_ost = ostrich()
obj_ost.intro()
obj_ost.flight()
```
## OUTPUT
<img width="948" height="275" alt="image" src="https://github.com/user-attachments/assets/a7818f53-e684-4e93-896b-e1df352ca6f4" />

## RESULT
Thus, the Python program was successfully executed to demonstrate class inheritance and method overriding by creating a parent class `Bird` and two child classes `Sparrow` and `Ostrich`. The output verified that the overridden `flight()` method in each subclass correctly displayed the distinct flying behaviors of different birds.
