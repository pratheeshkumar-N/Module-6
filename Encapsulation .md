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
```py

class Rectangle:
    def __init__(self):
        self.__length, self.__breadth = 5, 3
        print(self.__length)
        print(self.__breadth)
obj = Rectangle()
```
## Output

<img width="288" height="169" alt="446568190-02ce7632-1862-4409-a7c4-085e83e1c79d" src="https://github.com/user-attachments/assets/2c60d578-19b9-498a-9a68-a1389958e827" />

## Result
Thus, the program has been executed successfully.
