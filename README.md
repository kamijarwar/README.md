# 💰 Expense Tracker (Python Project)

A simple command-line Expense Tracker built using Python.  
This project allows users to add multiple expenses and calculates the total amount spent.

---

## 🚀 Features
- Add multiple expenses
- Continuous input until user stops
- Calculates total spending
- Simple and beginner-friendly logic

---

## 🧠 How it works
- User enters expense amount
- Program keeps adding it to total
- User can continue or stop by typing `y/n`
- Final total is displayed

---

## 🖥️ Code Example
```python
total = 0

while True:
    expense = float(input("Enter Expense Amount: "))
    total += expense

    choice = input("Add another expense? (y/n): ")
    if choice.lower() == "n":
        break

print("Total spent =", total)
