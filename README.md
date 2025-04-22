
# Python OOP Assignments 📚

This repository contains Python Object-Oriented Programming (OOP) assignments. These exercises cover a range of OOP concepts, including class creation, inheritance, abstraction, decorators, and more. ✨


### Colab Notebook 📓
Access the notebook here:  
🔗 [Link to Colab Notebook](https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX?usp=sharing)

---

# Python OOP Concepts - Project

## 📜 Table of Contents
1. [Using `self`](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=lp1tvec-7fvT&line=4&uniqifier=1)
2. [ Using `cls:`](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=1bjqjxIv70F-&line=4&uniqifier=1)
3. [Public Variables and Methods](#)
4. [Class Variables and Class Methods](#)
5. [Static Variables and Static Methods](#)
6. [Constructors and Destructors](#)
7. [Access Modifiers: Public, Private, and Protected](#)
8. [The `super()` Function](#)
9. [Abstract Classes and Methods](#)
10. [Instance Methods](#)
11. [Class Methods](#)
12. [Static Methods](#)
13. [Composition](#)
14. [Aggregation](#)
15. [MRO and Diamond Inheritance](#)
16. [Function Decorators](#)
17. [Class Decorators](#)
18. [Property Decorators](#)
19. [`callable()` and `__call__()`](#)
20. [Creating a Custom Exception](#)
21. [Make a Custom Class Iterable](#)

---


### 1. **Using `self`** 🧑‍💻  
- **Assignment**: Create a class `Student` with attributes `name` and `marks`. Use the `self` keyword to initialize these values via a constructor. Add a method `display()` that prints student details.

### 2. **Using `cls`** 🏷  
- **Assignment**: Create a class `Counter` that keeps track of how many objects have been created. Use a class variable and a class method with `cls` to manage and display the count.

### 3. **Public Variables and Methods** 🚗  
- **Assignment**: Create a class `Car` with a public variable `brand` and a public method `start()`. Instantiate the class and access both from outside the class.

### 4. **Class Variables and Class Methods** 🏦  
- **Assignment**: Create a class `Bank` with a class variable `bank_name`. Add a class method `change_bank_name(cls, name)` that allows changing the bank name. Show that it affects all instances.

### 5. **Static Variables and Static Methods** ➗  
- **Assignment**: Create a class `MathUtils` with a static method `add(a, b)` that returns the sum. No class or instance variables should be used.

### 6. **Constructors and Destructors** 🔨  
- **Assignment**: Create a class `Logger` that prints a message when an object is created (constructor) and another message when it is destroyed (destructor).

### 7. **Access Modifiers: Public, Private, and Protected** 🔒  
- **Assignment**: Create a class `Employee` with:
  - A public variable `name`
  - A protected variable `_salary`
  - A private variable `__ssn`
  Try accessing all three variables from an object of the class and document what happens.

### 8. **The `super()` Function** 🦸‍♂️  
- **Assignment**: Create a class `Person` with a constructor that sets the name. Inherit a class `Teacher` from it, add a subject field, and use `super()` to call the base class constructor.

### 9. **Abstract Classes and Methods** 🧑‍🏫  
- **Assignment**: Use the `abc` module to create an abstract class `Shape` with an abstract method `area()`. Inherit a class `Rectangle` that implements `area()`.

### 10. **Instance Methods** 🐕  
- **Assignment**: Create a class `Dog` with instance variables `name` and `breed`. Add an instance method `bark()` that prints a message including the dog's name.

---

Good luck with your assignments! 🚀 Keep pushing your limits! 💪
"""

# Save to a file
file_path = '/mnt/data/Python_OOP_Assignments.md'
with open(file_path, 'w') as file:
    file.write(content)

file_path



