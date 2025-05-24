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
    def __init__(self, length=10, breadth=5):
        self.__length = length
        self.__breadth = breadth
        print(" Using Encapsulation in Python:")
        print(" Length is:", self.__length)
        print(" Breadth is:", self.__breadth)

rect = Rectangle()
```

## Output
```
 Using Encapsulation in Python:
 Length is: 10
 Breadth is: 5
```

## Result
 By using encapsulation in Python, we can securely store and access private data inside a class without exposing it directly.

