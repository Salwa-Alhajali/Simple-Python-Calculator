# 🧮 Simple Python Calculator

A simple command-line calculator built with Python that performs basic arithmetic operations and allows continuous calculations.

---

## 🚀 Features

* Perform basic operations:

  * Addition ➕
  * Subtraction ➖
  * Multiplication ✖️
  * Division ➗
* Handles division by zero
* Continuous calculations using previous result
* Simple and beginner-friendly logic

---

## 📂 Project Structure

```id="u2p6p7"
calculator.py
README.md
```

---

## ▶️ Getting Started

### 1. Clone the repository

```bash id="g9j9zj"
git clone https://github.com/your-username/calculator.git
```

### 2. Navigate to the project folder

```bash id="b6h2m1"
cd calculator
```

### 3. Run the program

```bash id="t4o8vx"
python calculator.py
```

---

## 🧠 How It Works

* The program asks for the first number once.
* Then it enters a loop:

  * Choose an operation (`+`, `-`, `*`, `/`)
  * Enter the second number
  * Get the result
* The result becomes the new input for the next calculation.
* Enter `0` to exit the program.

---

## ⚠️ Error Handling

* Prevents division by zero
* Displays a message if the input is not a number

---

## 📌 Example

```id="r62k6f"
My calculator
enter the first number
10

enter your operation:
1- (*)
2- (-)
3- (+)
4- (/)
enter 0 to stop

enter the second number
5

= 50
```

---

## 🛠️ Future Improvements

* Support float numbers
* Improve input validation
* Fix spelling in messages
* Add graphical interface (GUI)
* Add history of calculations
