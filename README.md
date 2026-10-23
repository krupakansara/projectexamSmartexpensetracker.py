# 💰 Smart Expense Tracker Application

📊 **A Python-based application to record, manage, and analyze personal expenses.**

## 🌟 About the Project

The **Smart Expense Tracker Application** helps users monitor their spending and understand their expense patterns. It uses Python, NumPy, Pandas, Matplotlib, and Seaborn to organize expense records, calculate summaries, and create visualizations.

## 🎯 Project Objectives

- 🧾 Record daily expenses.
- 💾 Store expense data in a CSV file.
- 🧹 Validate and clean expense records.
- 💵 Calculate total and average expenses.
- 📊 Analyze category-wise spending.
- 🗓️ Analyze monthly spending trends.
- 🔎 Filter expenses using different conditions.
- 📈 Visualize spending patterns through charts.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Main programming language |
| 🧱 OOP | Organizing code using classes and objects |
| 🔢 NumPy | Numerical calculations |
| 🐼 Pandas | Data management and analysis |
| 📊 Matplotlib | Creating charts |
| 🎨 Seaborn | Statistical data visualization |
| 📄 CSV | Storing expense records |

## ✨ Main Features

### 1. ➕ Expense Management
- Add expense records with a date, amount, category, and description.
- Validate expense details.
- Save records in `expense.csv`.

### 2. 🧹 Data Cleaning
- Load existing expense records.
- Check required columns.
- Handle missing or invalid data.
- Standardize expense categories.

### 3. 📊 Expense Summary
Calculate and analyze:
- 💰 Total expenses
- 🧮 Average expense amount
- 🗂️ Category-wise spending
- 📉 Category-wise spending percentages
- 🗓️ Monthly expense totals
- 📈 Average monthly spending
- 🔢 Total number of expense records

### 4. 🔎 Expense Filtering

Filter expense records using:
- Category
- Start date
- End date
- Minimum amount
- Maximum amount

### 5. 📈 Data Visualization

The application is designed to generate four charts:

- 📊 **Bar Chart:** Total expenses by category.
- 📉 **Line Chart:** Spending trends over time.
- 🥧 **Pie Chart:** Spending distribution by category.
- 📶 **Histogram:** Frequency of expense amounts.

## 🗂️ Expense Categories

The application includes the following categories:

- 🍔 Food
- 🚌 Transport
- 💡 Utilities
- 🎬 Entertainment
- 🏥 Healthcare
- 🛍️ Shopping
- 📚 Education
- 📦 Other

## 📄 Dataset Information

The application uses a CSV file named `expense.csv`.

The dataset contains four columns:

| Column | Description |
|---|---|
| `date` | Date of the expense |
| `amount` | Amount spent |
| `category` | Expense category |
| `Description` | Details about the expense |

Example dataset:

```csv
date,amount,category,Description
2026-10-20,250,Food,Lunch
2026-10-21,80,Transport,Bus fare
```

## ⚙️ Installation

Install Python and the required libraries:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

## 🚀 How to Run the Project

1. Download or clone the project repository.
2. Open a terminal in the project folder.
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `set (1).ipynb`.
5. Run the notebook cells in order.
6. Review the output and visualizations.

## 📁 Project Structure

```text
Smart-Expense-Tracker/
│
├── set (1).ipynb    # Python project notebook
├── expense.csv      # Expense dataset
└── README.md        # Project documentation
```

The `expense.csv` file is designed to be created automatically if it does not already exist.

## 🎓 Python Concepts Demonstrated

- Classes and objects
- Exception handling
- File and CSV handling
- Input validation
- Data cleaning
- NumPy arrays and calculations
- Pandas DataFrames
- Grouping and filtering data
- Data visualization

## ⚠️ Important Note

Some method names and visualization statements in the current notebook may require corrections before all features run successfully. Test the application before submitting it as a fully working project.

## 👩‍💻 Author

Created as a Python learning project. 💻

---

⭐ **Thank you for checking out the Smart Expense Tracker Application!** 🚀
