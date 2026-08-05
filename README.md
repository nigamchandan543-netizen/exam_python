# E-Library Data Insights Dashboard

*Project Title:* E-Library Data Insights Dashboard  
*Institution:* Red & White Skill Education  
*Exam:* Practical Exam – Set B  
*Level:* Beginner

---

## Objective

This project is a simple Python program that analyzes library book borrowing data.

It helps us understand:
- Which books are borrowed the most
- Average borrowing time
- Trends over months
- Popular genres

---

## What This Project Uses

- *Control Structures* (if, for loops)
- *OOP* (Class and Methods)
- *NumPy* (for average and standard deviation)
- *Pandas* (for reading and cleaning data)
- *Matplotlib & Seaborn* (for graphs)

---

## Files in This Project

| File Name                    | Description                          |
|-----------------------------|--------------------------------------|
| library_dashboard.py      | Main Python code                     |
| library_transactions.csv  | Sample library data                  |
| README.md                 | This file (project explanation)      |

---

## How to Run the Project

### Step 1: Install required libraries

Open terminal and type:

```bash

#Keep both files in same folder
E_library_dashboard
│
├── library_dashboard.py
└── library_transactions.csv
Step 3: Run the program
python library_dashboard.py
Features of the Program
1. Data Loading and Validation
Reads the CSV file
Checks if the file is correct
Removes missing or wrong data
Cleans the data automatically
2. Calculate Statistics
Finds the most borrowed book
Calculates average borrowing duration using NumPy
Finds the busiest day of the week
3. Filter Transactions
Can filter data by genre
Can filter by date range
Can filter by borrowing duration
4. Generate Report
Shows total transactions
Shows top 5 books
Shows books by genre
5. Visualizations (Graphs)
Bar Chart → Top 5 most borrowed books
Line Graph → Borrowing trends over months
Pie Chart → Distribution by genre
Heatmap → Activity by day of week
Dataset Details
The CSV file contains these columns:
Transaction ID
Date (YYYY-MM-DD)
User ID
Book Title
Genre
Borrowing Duration (Days)
Class and Methods
Class Name: LibraryDashboard
Method
Purpose
load_data()
Load and clean the CSV file
calculate_statistics()
Calculate important numbers
filter_transactions()
Filter data as per condition
generate_report()
Print summary report
plot_top5_books()
Bar chart of top 5 books
plot_monthly_trends()
Line graph of monthly trends
plot_genre_pie()
Pie chart of genres
plot_heatmap()
Heatmap of daily activity
Example Output
When you run the program, you will see:
Data loading messages
Statistics (most borrowed book, average duration etc.)
Full report
Filtered data example
Four graphs will open one by one
