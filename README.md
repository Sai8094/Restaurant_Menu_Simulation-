# 🍽️ Restaurant Menu Simulation in Java

## 📌 Overview
This project simulates a **restaurant ordering system** where customers can order different food items.  
Each item (Pizza, Burger, Pasta) has a **price, preparation time, and unique ingredients**.  
The system demonstrates **core OOP principles** like **Abstraction, Inheritance, Polymorphism, and Encapsulation**.

---

## 🛠 Features
- Supports three food items:
  - 🍕 **Pizza**
  - 🍔 **Burger**
  - 🍝 **Pasta**
- Each food item has:
  - **Price**
  - **Preparation time**
  - **Ingredients list**
- Ordering system:
  - ✅ Place an order for any item
  - ⏱ Show cooking time
  - 💰 Display item price
  - 📑 Show details of ordered item(s)

---

## 🏗 Design
- **FoodItem (Abstract Class / Interface)**  
  - Methods:  
    - `getPrice()`  
    - `getPreparationTime()`  
    - `getIngredients()`  
- **Pizza, Burger, Pasta (Subclasses)**  
  - Provide their own **price**, **time**, and **ingredients**  
- **Restaurant (Class)**  
  - Takes orders using **polymorphism**  
  - Displays order details and preparation information  
- **Main (Simulation Class)**  
  - Demonstrates ordering multiple items  

---

## 🎯 Core Logic
- **Abstraction** → `FoodItem` defines the common structure for all menu items.  
- **Inheritance** → `Pizza`, `Burger`, and `Pasta` extend or implement `FoodItem`.  
- **Polymorphism** → All food items can be referenced through `FoodItem` type.  
- **Encapsulation** → Price and preparation time are private, accessed via getters.  

---

## 📚 OOP Concepts Used
- **Abstraction** → `FoodItem` interface/abstract class hides implementation.  
- **Inheritance** → Subclasses (`Pizza`, `Burger`, `Pasta`) reuse structure.  
- **Polymorphism** → Any `FoodItem` can be ordered with the same method.  
- **Encapsulation** → Sensitive details (price, prep time) hidden inside classes.  
