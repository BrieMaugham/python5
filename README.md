# 🐍 Python Week 5 Assignments

I created this repository to showcase my understanding of Python **Object-Oriented Programming (OOP)** concepts and **Polymorphism**. It contains two major activities:  
1. Designing a custom class with attributes, methods, and inheritance.  
2. Demonstrating polymorphism using different classes that share the same method but behave differently.  


## 📂 Repository Structure

pythonweek3/
├── class_design.py # Assignment 1: Custom class with attributes, methods, and inheritance
├── polymorphism_challenge.py # Assignment 2: Polymorphism demonstration
└── README.md # Project documentation

## 🏗️ Assignment 1: Design Your Own Class

I designed a Python class to demonstrate how OOP concepts work in real-world scenarios.  

### 🔹 Features
- I created a class that represents a real-world object (e.g., **Smartphone**).  
- I used a **constructor (`__init__`)** to initialize unique attributes for each object.  
- I implemented **methods** to define class behaviors.  
- I added **inheritance** to explore encapsulation and code reusability.  

📌 Example:
```python
phone1 = Smartphone("iPhone 15", "Apple", 256)
phone1.display_info()
🎭 Assignment 2: Polymorphism Challenge
I demonstrated polymorphism by creating multiple classes that implement a method with the same name but different behaviors.

🔹 Features
I created Animal and Vehicle classes with a move() method.

Each subclass (e.g., Car, Plane, Dog, Bird) overrides move() to perform unique actions.

This shows how polymorphism makes code flexible and scalable.

📌 Example:
car = Car()
plane = Plane()

for vehicle in [car, plane]:
    vehicle.move()
Output:
Driving 🚗
Flying ✈️
🛠️ Technologies Used
Python 3.x

OOP principles: Classes, Objects, Inheritance, Polymorphism

Git & GitHub for version control

🚀 How to Run This Project
Clone this repository:

git clone https://github.com/BrieMaugham/pythonweek3.git
Navigate to the folder:

cd pythonweek3
Run any of the assignments:

python class_design.py
python polymorphism_challenge.py
✨ Outcomes
By completing this assignment, I:

Strengthened my understanding of Object-Oriented Programming in Python.

Practiced inheritance and encapsulation to build reusable code.

Used polymorphism to make programs dynamic and maintainable.

Gained confidence in writing clean, structured, and well-documented Python code.

👩🏽‍💻 Created by: Bridie Maugham Dibora
