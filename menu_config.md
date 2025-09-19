\# 📝 Expense Tracker Menu Options

This file explains all the options available when running
\`expense_tracker.py\`.

\-\--

\## Main Menu

When you run the program, you will see:

1\. \*\*Add New Expense\*\*  - Enter a category (Food, Travel, Study,
Other)  - Enter the amount spent  - Add an optional note  - Saves the
expense to the database

2\. \*\*View All Expenses\*\*  - Displays all recorded expenses  - Shows
date, category, amount, and note  - Displays total expenses

3\. \*\*Category Breakdown (with chart)\*\*  - Shows total spent per
category  - Displays a bar chart with values labeled

4\. \*\*Weekly & Monthly Analysis\*\*  - Shows total spending per week
and per month  - Displays side-by-side bar charts for trends

5\. \*\*Search/Filter Expenses\*\*  - Filter by \*\*category\*\* or
\*\*date range\*\*  - Shows total for filtered results

6\. \*\*Delete Expense\*\*  - Shows last 10 expenses with ID  - Enter ID
to delete an expense  - Confirms before deletion

7\. \*\*Exit Program\*\*  - Closes the expense tracker

\-\--

\## Notes - All data is stored in an SQLite database (\`expenses.db\`).
 - Visualizations require \*\*matplotlib\*\* installed.  - User input is
validated for categories and amounts.

\-\--
