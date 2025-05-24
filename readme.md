1. Personal Finance Manager

A simple Java Swing application to track income and expenses, view a summary balance, and manage personal finances via an easy-to-use graphical user interface (GUI).

2. Features

- User login authentication (default credentials: **admin / 1234**)
- Add income entries
- Add expense entries
- View summary of total income, total expenses, and current balance
- Simple and intuitive GUI using Java Swing

3. Getting Started

.. Prerequisites

- Java Development Kit (JDK) 8 or higher
- IDE like IntelliJ IDEA, Eclipse, or command line Java compiler

.. Running the Application

1. Clone or download the repository.
2. Compile all `.java` files.
3. Run the `Main` class to launch the login screen.
4. Login using:
   - Username: `admin`
   - Password: `1234`
5. Use the Dashboard to add income, expenses, or view summary.

---

4.  Project Structure

├── Main.java # Entry point to start the application
├── FinanceManager.java # Static class to manage total income and expenses
├── LoginFrame.java # GUI for user login
├── DashboardFrame.java # Main dashboard with navigation buttons
├── IncomeFrame.java # GUI to add income amount
├── ExpenseFrame.java # GUI to add expense amount
└── SummaryFrame.java # GUI to display financial summary

