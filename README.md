
# Python OOP Assignments 📚

This repository contains Python Object-Oriented Programming (OOP) assignments. These exercises cover a range of OOP concepts, including class creation, inheritance, abstraction, decorators, and more. ✨


### Colab Notebook 📓
Access the notebook here:  
🔗 [Link to Colab Notebook](https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX?usp=sharing)

---



## 📜 Table of Contents
1. [Using self](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=lp1tvec-7fvT&line=4&uniqifier=1)
2. [Using cls](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=1bjqjxIv70F-&line=4&uniqifier=1)
3. [Public Variables and Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=4xiyl1ke73ZH&line=3&uniqifier=1)
4. [Class Variables and Class Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=kz1IW0W-77GW&line=3&uniqifier=1)
5. [Static Variables and Static Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=wjPtJUEO79vS&line=2&uniqifier=1)
6. [Constructors and Destructors](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=e35P1BJ-8Dwd&line=2&uniqifier=1)
7. [Access Modifiers: Public, Private, and Protected](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=oW2_TwND8VY2&line=4&uniqifier=1)
8. [The `super()` Function](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=lIE_murM8YPw&line=4&uniqifier=1)
9. [Abstract Classes and Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=cyAnHX_M8bEv&line=8&uniqifier=1)
10. [Instance Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=LxnOJT2k8d2r&line=2&uniqifier=1)
11. [Class Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=IJ3ZK6998gyA&line=3&uniqifier=1)
12. [Static Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=25hQ0KBE8jmb&line=3&uniqifier=1)
13. [Composition](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=84if5Y3K8mAc&line=11&uniqifier=1)
14. [Aggregation](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=SmO76AmR8piN&line=3&uniqifier=1)
15. [MRO and Diamond Inheritance](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=P9UiwQmE8snr&line=3&uniqifier=1)
16. [Function Decorators](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=mIrObq5B8vbr&line=4&uniqifier=1)
17. [Class Decorators](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=jPmDerW88yJL&line=11&uniqifier=1)
18. [Property Decorators](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=WtAZiPCA82Xh&line=5&uniqifier=1)
19. [`callable()` and `__call__()`](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=new1wYI285hd&line=4&uniqifier=1)
20. [Creating a Custom Exception](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=nVlmG3j188Y-&line=7&uniqifier=1)
21. [Make a Custom Class Iterable](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=Tlg0RoXn8_RU&line=9&uniqifier=1)

---
















# Python OOP Concepts - Project

## 📜 Table of Contents
1. [Using self](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=lp1tvec-7fvT&line=4&uniqifier=1)
2. [Using cls](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=1bjqjxIv70F-&line=4&uniqifier=1)
3. [Public Variables and Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=4xiyl1ke73ZH&line=3&uniqifier=1)
4. [Class Variables and Class Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=kz1IW0W-77GW&line=3&uniqifier=1)
5. [Static Variables and Static Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=wjPtJUEO79vS&line=2&uniqifier=1)
6. [Constructors and Destructors](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=e35P1BJ-8Dwd&line=2&uniqifier=1)
7. [Access Modifiers: Public, Private, and Protected](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=oW2_TwND8VY2&line=4&uniqifier=1)
8. [The `super()` Function](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=lIE_murM8YPw&line=4&uniqifier=1)
9. [Abstract Classes and Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=cyAnHX_M8bEv&line=8&uniqifier=1)
10. [Instance Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=LxnOJT2k8d2r&line=2&uniqifier=1)
11. [Class Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=IJ3ZK6998gyA&line=3&uniqifier=1)
12. [Static Methods](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=25hQ0KBE8jmb&line=3&uniqifier=1)
13. [Composition](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=84if5Y3K8mAc&line=11&uniqifier=1)
14. [Aggregation](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=SmO76AmR8piN&line=3&uniqifier=1)
15. [MRO and Diamond Inheritance](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=P9UiwQmE8snr&line=3&uniqifier=1)
16. [Function Decorators](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=mIrObq5B8vbr&line=4&uniqifier=1)
17. [Class Decorators](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=jPmDerW88yJL&line=11&uniqifier=1)
18. [Property Decorators](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=WtAZiPCA82Xh&line=5&uniqifier=1)
19. [`callable()` and `__call__()`](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=new1wYI285hd&line=4&uniqifier=1)
20. [Creating a Custom Exception](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=nVlmG3j188Y-&line=7&uniqifier=1)
21. [Make a Custom Class Iterable](#https://colab.research.google.com/drive/1P_dH5oUycTXT5XFEuYYWKcBQFHHcL0OX#scrollTo=Tlg0RoXn8_RU&line=9&uniqifier=1)

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



