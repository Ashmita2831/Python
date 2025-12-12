💰 Expense Tracker : Python Tkinter App

A simple and user-friendly Expense Tracker application built using
Python, Tkinter, and Pandas.
This tool allows users to record daily expenses, view all expense
entries, visualize spending trends, and get a summary of total and
average expenses.

🚀 Features
✔️ Add Expenses
Users can enter: 
- Date (YYYY-MM-DD)
- Category (Food,
Transport, Shopping, Bills, etc.)
 - Amount (₹)
These are saved inside expenses.csv automatically.

✔️ View All Expenses
Displays all saved expenses in a table-like format using 'ttk.Treeview'.

✔️ Expense Summary
Shows: Total spent (₹) - Average expense (₹)

✔️ Expense Charts
Generates three types of visual charts using 'Matplotlib' & 'Seaborn':
1.  Bar Chart - Total expenses by category
2.  Pie Chart - Category-wise expense percentage
3.  Line Chart - Expenses over time

📁 File: 'expenses.csv'
Automatically created if not present.
Columns:
    Date, Category, Amount

🛠 Technologies Used
-   Python 3
-   Tkinter -- GUI framework
-   Pandas -- Data handling
-   Matplotlib -- Chart plotting
-   Seaborn -- Enhanced visual styling

▶️ How to Run

1.  Install required libraries:
    pip install pandas matplotlib seaborn
2.  Save the script as 'expense_tracker.py'
3.  Run:
    python expense_tracker.py

📊 Charts Generated

-   Total spent per category
-   Percentage distribution (pie chart)
-   Expense trend across dates

✔️ Error Handling

Checks for: - Missing input fields
- Non-numeric amount values
- Empty dataset

📌 Future Improvements

-   Edit/Delete entries
-   Monthly filtering
-   Export to Excel/PDF
-   Multi-user login
