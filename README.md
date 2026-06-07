# 📈 Stock Portfolio Tracker

## 📌 Project Overview

The **Stock Portfolio Tracker** is a simple Python application that helps users calculate the total value of their stock investments. Users can enter stock symbols and quantities, and the program calculates the investment value using predefined stock prices stored in a dictionary.

This project was developed as part of the **CodeAlpha Python Programming Internship** to demonstrate fundamental Python programming concepts such as dictionaries, user input, arithmetic operations, and file handling.

---

## 🎯 Objective

Build a simple stock tracking system that:

* Accepts stock names from the user.
* Accepts the quantity of shares owned.
* Uses predefined stock prices.
* Calculates the total investment value.
* Displays the investment summary.
* Optionally saves results to a `.txt` or `.csv` file.

---

## 🛠️ Features

✅ User inputs stock symbols and quantities

✅ Uses a hardcoded stock price dictionary

✅ Calculates total investment value

✅ Displays stock details and portfolio value

✅ Saves results to a text file (`portfolio_report.txt`)

✅ Saves results to a CSV file (`portfolio.csv`)

✅ Handles invalid stock symbols

✅ Beginner-friendly and easy-to-understand code

---

## 📚 Technologies Used

* Python 3
* Dictionary Data Structure
* Input/Output Operations
* Arithmetic Calculations
* File Handling
* CSV Module

---


---

## 🚀 How It Works

### Step 1: Define Stock Prices

The program stores stock prices in a dictionary:

```python
stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOG": 140,
    "MSFT": 400
}
```

### Step 2: Get User Input

The user enters:

* Stock Symbol
* Quantity of Shares

Example:

```text
Enter Stock Name: AAPL
Enter Quantity: 5
```

### Step 3: Calculate Investment

Formula:

```text
Investment Value = Stock Price × Quantity
```

Example:

```text
180 × 5 = 900
```

### Step 4: Display Results

Example Output:

```text
Stock: AAPL
Quantity: 5
Price per Share: $180
Total Investment Value: $900
```

### Step 5: Save Data

The program can save results in:

* Text File (`portfolio_report.txt`)
* CSV File (`portfolio.csv`)

---

## 📊 Sample Output

```text
Enter Stock Name: TSLA
Enter Quantity: 4

Stock: TSLA
Quantity: 4
Price per Share: $250
Total Investment Value: $1000

Data saved successfully.
```

---

## 📄 Sample CSV Output

```csv
Stock,Quantity,Price,Total
TSLA,4,250,1000
```

---

## 🧠 Key Concepts Learned

### Dictionary

Used to store stock names and prices.

```python
stock_prices["AAPL"]
```

### User Input

Used to collect stock details.

```python
input()
```

### Conditional Statements

Used to validate stock symbols.

```python
if stock_name in stock_prices:
```

### Arithmetic Operations

Used to calculate investment values.

```python
total = price * quantity
```

### File Handling

Used to save portfolio information.

```python
with open("portfolio_report.txt", "w") as file:
```

---

## 🔮 Future Enhancements

* Add more stock symbols
* Fetch real-time stock prices using APIs
* Create graphical reports and charts
* Support multiple stock entries
* Build a graphical user interface (GUI)
* Store portfolio history in a database

---

## 🎓 Internship Task Information

**Internship:** CodeAlpha Python Programming Internship

**Task:** Task 2 – Stock Portfolio Tracker

**Domain:** Python Programming

**Difficulty Level:** Beginner

---

## 📈 Learning Outcome

This project strengthened my understanding of:

* Python Fundamentals
* Data Structures
* User Interaction
* File Management
* Problem Solving
* Financial Data Calculations

It demonstrates how basic programming concepts can be used to build practical applications for tracking and managing investments.

---

## 👨‍💻 Author

Developed as part of the **CodeAlpha Python Programming Internship**.

⭐ If you found this project useful, consider giving it a star on GitHub!
