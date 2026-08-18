# 🏥 BMI Calculator

A Python-based **Body Mass Index (BMI) Calculator** that calculates a user's BMI based on their height and weight and classifies the result into different health categories.

This project is designed in two levels:

* 🟢 **Beginner:** Command-line BMI calculator using Python
* 🔵 **Advanced:** GUI application with data persistence and BMI trend visualization

---

## 📌 Project Objective

The objective of this project is to develop a Python application that calculates a user's **Body Mass Index (BMI)** and classifies it into appropriate health categories.

The beginner version focuses on Python fundamentals such as `input()`, variables, arithmetic operations, and conditional statements.

The advanced version provides a graphical interface along with **data storage and BMI trend visualization**.

---

## 🧮 What is BMI?

BMI (Body Mass Index) is a value calculated from a person's weight and height.

### Formula

```text
BMI = Weight (kg) / Height² (m)
```

For example:

```text
Weight = 60 kg
Height = 1.65 m

BMI = 60 / (1.65 × 1.65)
BMI ≈ 22.04
```

### BMI Categories

| BMI Range      | Category      |
| -------------- | ------------- |
| Below 18.5     | Underweight   |
| 18.5 – 24.9    | Normal Weight |
| 25.0 – 29.9    | Overweight    |
| 30.0 and above | Obesity       |

> **Note:** BMI is a general screening measure and does not provide a complete assessment of an individual's health.

---

## ✨ Features

### 🟢 Beginner Version

* Calculate BMI using height and weight
* Accept user input through the command line
* Display BMI value
* Classify BMI into health categories
* Simple and beginner-friendly Python implementation

### 🔵 Advanced Version

* User-friendly graphical interface
* BMI calculation
* BMI category classification
* Store previous BMI records
* View BMI history
* Visualize BMI trends using graphs
* Persistent data storage using SQLite or CSV
* Input validation and error handling

---

## 🛠️ Technologies Used

### Beginner

* Python
* `input()`
* Variables
* Arithmetic operations
* Conditional statements

### Advanced

* Python
* Tkinter / PyQt5
* Matplotlib
* SQLite3 / CSV
* Python standard libraries

---

## 📂 Project Structure

```text
BMI-Calculator/
│
├── README.md
├── bmi_calculator.py
│
├── advanced/
│   ├── bmi_gui.py
│   ├── database.py
│   └── bmi_history.db
│
├── screenshots/
│   └── bmi-calculator.png
│
└── requirements.txt
```

> The exact folder structure may vary depending on your implementation.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/BMI-Calculator.git
```

### 2. Navigate to the Project Folder

```bash
cd BMI-Calculator
```

### 3. Run the Beginner Version

```bash
python bmi_calculator.py
```

### 4. Run the Advanced Version

```bash
python advanced/bmi_gui.py
```

---

## 💻 Beginner Example

```text
Enter your weight in kg: 60
Enter your height in meters: 1.65

Your BMI is: 22.04
Category: Normal Weight
```

---

## 📊 Advanced Version

The advanced version provides a graphical interface where users can:

1. Enter their weight and height.
2. Calculate their BMI.
3. View their BMI category.
4. Save BMI records.
5. View previous BMI results.
6. Analyze BMI changes through a graph.

### Example Workflow

```text
Enter Weight
     ↓
Enter Height
     ↓
Calculate BMI
     ↓
Classify BMI
     ↓
Save Result
     ↓
Display BMI Trend
```

---

## 📈 BMI Trend Visualization

The advanced version uses **Matplotlib** to display BMI history.

Example:

```text
BMI
30 |                 ●
28 |             ●
26 |         ●
24 |     ●
22 | ●
   +-------------------------
      Day 1  Day 2  Day 3  Day 4
```

This allows users to observe how their BMI changes over time.

---

## 💾 Data Persistence

BMI records can be stored using:

* **SQLite3** — recommended for structured data
* **CSV** — simple and beginner-friendly

Example stored information:

| Date       | Weight | Height |   BMI | Category |
| ---------- | -----: | -----: | ----: | -------- |
| 18-08-2026 |  60 kg | 1.65 m | 22.04 | Normal   |
| 25-08-2026 |  61 kg | 1.65 m | 22.41 | Normal   |

---

## 🔐 Input Validation

The application should handle invalid inputs such as:

* Empty values
* Negative weight
* Negative height
* Zero height
* Non-numeric input

Example:

```text
Enter your weight: abc

❌ Please enter a valid number.
```

---

## 🎯 Learning Outcomes

Through this project, you can learn:

* Python programming fundamentals
* User input handling
* Conditional statements
* Functions
* Exception handling
* GUI development
* Database operations
* Data visualization
* Basic project structure
* Git and GitHub

---

## 🔮 Future Enhancements

The project can be further improved by adding:

* 👤 User profiles
* 📅 Daily/weekly/monthly BMI tracking
* 📊 Advanced health dashboards
* 📈 Interactive BMI charts
* 🎨 Improved GUI design
* 🌙 Dark mode
* 📄 Generate BMI reports
* 🔔 Health reminders
* ☁️ Cloud-based data storage
* 📱 Mobile application version

---

## 📸 Screenshots

Add screenshots of your application here:

```markdown
![BMI Calculator](screenshots/bmi-calculator.png)
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Create a Pull Request.

---

## 📜 License

This project is created for **educational and learning purposes**.

---

## 👩‍💻 Author

**Your Name**

GitHub: `https://github.com/# 🏥 BMI Calculator

A Python-based **Body Mass Index (BMI) Calculator** that calculates a user's BMI based on their height and weight and classifies the result into different health categories.

This project is designed in two levels:

* 🟢 **Beginner:** Command-line BMI calculator using Python
* 🔵 **Advanced:** GUI application with data persistence and BMI trend visualization

---

## 📌 Project Objective

The objective of this project is to develop a Python application that calculates a user's **Body Mass Index (BMI)** and classifies it into appropriate health categories.

The beginner version focuses on Python fundamentals such as `input()`, variables, arithmetic operations, and conditional statements.

The advanced version provides a graphical interface along with **data storage and BMI trend visualization**.

---

## 🧮 What is BMI?

BMI (Body Mass Index) is a value calculated from a person's weight and height.

### Formula

```text
BMI = Weight (kg) / Height² (m)
```

For example:

```text
Weight = 60 kg
Height = 1.65 m

BMI = 60 / (1.65 × 1.65)
BMI ≈ 22.04
```

### BMI Categories

| BMI Range      | Category      |
| -------------- | ------------- |
| Below 18.5     | Underweight   |
| 18.5 – 24.9    | Normal Weight |
| 25.0 – 29.9    | Overweight    |
| 30.0 and above | Obesity       |

> **Note:** BMI is a general screening measure and does not provide a complete assessment of an individual's health.

---

## ✨ Features

### 🟢 Beginner Version

* Calculate BMI using height and weight
* Accept user input through the command line
* Display BMI value
* Classify BMI into health categories
* Simple and beginner-friendly Python implementation

### 🔵 Advanced Version

* User-friendly graphical interface
* BMI calculation
* BMI category classification
* Store previous BMI records
* View BMI history
* Visualize BMI trends using graphs
* Persistent data storage using SQLite or CSV
* Input validation and error handling

---

## 🛠️ Technologies Used

### Beginner

* Python
* `input()`
* Variables
* Arithmetic operations
* Conditional statements

### Advanced

* Python
* Tkinter / PyQt5
* Matplotlib
* SQLite3 / CSV
* Python standard libraries

---

## 📂 Project Structure

```text
BMI-Calculator/
│
├── README.md
├── bmi_calculator.py
│
├── advanced/
│   ├── bmi_gui.py
│   ├── database.py
│   └── bmi_history.db
│
├── screenshots/
│   └── bmi-calculator.png
│
└── requirements.txt
```

> The exact folder structure may vary depending on your implementation.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/BMI-Calculator.git
```

### 2. Navigate to the Project Folder

```bash
cd BMI-Calculator
```

### 3. Run the Beginner Version

```bash
python bmi_calculator.py
```

### 4. Run the Advanced Version

```bash
python advanced/bmi_gui.py
```

---

## 💻 Beginner Example

```text
Enter your weight in kg: 60
Enter your height in meters: 1.65

Your BMI is: 22.04
Category: Normal Weight
```

---

## 📊 Advanced Version

The advanced version provides a graphical interface where users can:

1. Enter their weight and height.
2. Calculate their BMI.
3. View their BMI category.
4. Save BMI records.
5. View previous BMI results.
6. Analyze BMI changes through a graph.

### Example Workflow

```text
Enter Weight
     ↓
Enter Height
     ↓
Calculate BMI
     ↓
Classify BMI
     ↓
Save Result
     ↓
Display BMI Trend
```

---

## 📈 BMI Trend Visualization

The advanced version uses **Matplotlib** to display BMI history.

Example:

```text
BMI
30 |                 ●
28 |             ●
26 |         ●
24 |     ●
22 | ●
   +-------------------------
      Day 1  Day 2  Day 3  Day 4
```

This allows users to observe how their BMI changes over time.

---

## 💾 Data Persistence

BMI records can be stored using:

* **SQLite3** — recommended for structured data
* **CSV** — simple and beginner-friendly

Example stored information:

| Date       | Weight | Height |   BMI | Category |
| ---------- | -----: | -----: | ----: | -------- |
| 18-08-2026 |  60 kg | 1.65 m | 22.04 | Normal   |
| 25-08-2026 |  61 kg | 1.65 m | 22.41 | Normal   |

---

## 🔐 Input Validation

The application should handle invalid inputs such as:

* Empty values
* Negative weight
* Negative height
* Zero height
* Non-numeric input

Example:

```text
Enter your weight: abc

❌ Please enter a valid number.
```

---

## 🎯 Learning Outcomes

Through this project, you can learn:

* Python programming fundamentals
* User input handling
* Conditional statements
* Functions
* Exception handling
* GUI development
* Database operations
* Data visualization
* Basic project structure
* Git and GitHub

---

## 🔮 Future Enhancements

The project can be further improved by adding:

* 👤 User profiles
* 📅 Daily/weekly/monthly BMI tracking
* 📊 Advanced health dashboards
* 📈 Interactive BMI charts
* 🎨 Improved GUI design
* 🌙 Dark mode
* 📄 Generate BMI reports
* 🔔 Health reminders
* ☁️ Cloud-based data storage
* 📱 Mobile application version

---

## 📸 Screenshots

Add screenshots of your application here:

```markdown
![BMI Calculator](screenshots/bmi-calculator.png)
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Create a Pull Request.

---

## 📜 License

This project is created for **educational and learning purposes**.

---

## 👩‍💻 Author

**Your Name**

GitHub: `https://github.com/simicareddy-cyber`

---

⭐ If you found this project useful, consider giving the repository a **star**!
`

---

⭐ If you found this project useful, consider giving the repository a **star**!
