Financial Tracker 📊
A simple command-line financial tracker that allows users to log transactions, categorize them as income or expenses, view transaction summaries, and generate visual reports. The data is stored in a CSV file for easy access and analysis.

📌 Features
✔ Add Transactions – Log income & expenses with date, amount, category, and description
✔ View Transactions – Filter by date range and get a financial summary
✔ Generate Reports – Plot income & expenses over time using Matplotlib
✔ Data Persistence – Stores transactions in a CSV file for long-term tracking
✔ Error Handling – Input validation for date, amount, and category

🛠️ Technologies Used
Python 🐍
Pandas – For data handling
CSV Module – For storing transactions
Matplotlib – For data visualization
Datetime Module – For handling date inputs

📌 How to Use
Adding a New Transaction
Run the program
Choose option 1. Add a new transaction
Enter the date (dd-mm-yyyy)
Enter the amount
Select category:
I for Income
E for Expense
Enter a description (optional)
Viewing Transactions & Summary
Choose option 2. View transactions and summary within a date range
Enter a start date and end date
See all transactions within that range along with:
Total Income
Total Expenses
Net Balance
Generating a Transaction Plot
After viewing transactions, enter 'y' when asked:
css
Copy
Do you want to see a plot? (y/n): y
A graph showing income & expenses over time will appear

📁 Project Structure
bash
Copy
financial-tracker/
│── main.py          # Main script to run the app
│── data_entry.py    # Handles user input & validation
│── finance_data.csv # Stores financial transactions (created automatically)
│── README.md        # Project documentation

🛠️ Future Enhancements
🚀 Add a web-based UI using Flask/Django
📊 Export reports to PDF or Excel
🔗 Integrate with banking APIs for auto-tracking

👨‍💻 Contributing
Got an idea? Contributions are welcome! Fork the repo, make changes, and submit a PR.
