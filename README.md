
# Bank Management System

## Overview
The **Bank Management System** is a basic C-based application designed to manage bank accounts through file handling. It allows users to perform fundamental banking operations such as adding new accounts, viewing existing account details, and conducting deposits or withdrawals. This project serves as an educational demonstration of file manipulation, structured data storage, and basic user input handling in C.

## Features
- **Add New Accounts:** Create and store account records with the account holder's name, account number, and balance.
- **View Account Information:** Retrieve and display account details based on the account number.
- **Deposit and Withdrawal:** Update account balances by performing deposit or withdrawal transactions.
- **File-Based Data Management:** Uses text files to store and retrieve account data, providing a persistent storage solution.

## Getting Started
### Prerequisites
To compile and run the program, you will need:
- A C compiler (e.g., GCC)
- A terminal or command-line interface

### Compilation
Use the following command to compile the program:
```bash
gcc -o BankManagementSystem bank_management_system.c
```

### Running the Program
Execute the compiled program with:
```bash
./BankManagementSystem
```

Follow the on-screen prompts to perform various operations.

## Usage
1. **Adding an Account:**  
   Select the option to add a new account, then input the account holder's name, account number, and initial balance.
2. **Viewing Accounts:**  
   Enter the account number to retrieve and display the account's details.
3. **Deposits and Withdrawals:**  
   Choose the corresponding option and specify the amount to update the balance for the selected account.

## File Structure
- Account data is stored in a plain text file (`account.txt`), where each line contains an account's information in the format:
  ```
  Name Account_Number Balance
  ```
- For transaction safety, a temporary file is used to update account information.

## Future Enhancements
- **Data Encryption:** Implement encryption for secure storage of account details.
- **User Authentication:** Add a login system for different user roles (e.g., admin, customer).
- **Database Integration:** Migrate from file-based storage to a database solution (e.g., SQLite, MySQL).
- **Enhanced Interface:** Develop a graphical user interface (GUI) using a C-based toolkit (e.g., GTK).

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


