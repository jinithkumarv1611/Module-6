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
```python
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def display(self):
        print("Length =", self.__length)
        print("Breadth =", self.__breadth)


r = Rectangle(10, 5)

r.display()
```

## Output
<img width="1219" height="503" alt="image" src="https://github.com/user-attachments/assets/54c10828-2e01-4c89-ab66-94a4f83dbb32" />

## Result
Thus the given program executed Successfully.
