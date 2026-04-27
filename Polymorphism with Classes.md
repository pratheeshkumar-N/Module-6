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
```py

class Beans:
    def type(self): print("Vegetable")
    def color(self): print("Green")

class Mango:
    def type(self): print("Fruit")
    def color(self): print("Yellow")

def func(obj):
    obj.type(); obj.color()

func(Beans())
func(Mango())
```
## Output

<img width="342" height="224" alt="446575065-6b61d724-17ee-4dac-a759-9773b622ca57" src="https://github.com/user-attachments/assets/281bae3e-8c93-4a28-a3f7-153d01bb4387" />

## Result
Thus, the program is executed successfully.
