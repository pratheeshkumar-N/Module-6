# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```py

class Fish:
    def type(self): print("fish")

class Shark(Fish):
    def type(self): print("shark")

for obj in [Fish(), Shark()]:
    obj.type()
```
## OUTPUT

<img width="482" height="273" alt="446569816-ce389803-873d-4117-ba9d-024681b48a19" src="https://github.com/user-attachments/assets/53e53d04-56c9-422e-aeb7-d1de57f5f106" />

## RESULT
Thus, the program is executed successfully.
