🏦 Simple Bank Account Management System (C++)
This is a basic Bank Account Management System implemented in C++. It allows creating and managing bank accounts for multiple users with features like deposit, withdrawal, FDR (Fixed Deposit Receipt), and DPS (Deposit Pension Scheme).

🚀 Features
Create multiple bank accounts (predefined names)

Deposit and withdraw money

Create FDR with 8% annual interest

Create DPS with 6% interest over the full duration

Display all user details

🧾 Functionalities
setDetails(name, accountNumber, balance) – Initialize user account

deposit(amount) – Add money to balance

withdraw(amount) – Subtract money from balance (if sufficient)

createFDR(amount, years) – Fixed deposit with 8% annual interest

createDPS(monthlyAmount, years) – Monthly deposit scheme with 6% total interest

showDetails() – View user details

📁 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Compile the code:

bash
Copy
Edit
g++ -o bank BankAccount.cpp
Run the executable:

bash
Copy
Edit
./bank
🧑‍💻 Example Output
yaml
Copy
Edit
Abir Mollik deposited 500. New balance: 1500
Abir Mollik withdrew 200. New balance: 1300
Abir Mollik created FDR for 2 years. Maturity amount: 1816
Abir Mollik created DPS for 3 years. Total after maturity: 3816
...
All User Details:
Name: Abir Mollik, Account No: 1001, Balance: 600
...
🛠️ Technologies Used
C++

Standard Template Library (STL)

g++

