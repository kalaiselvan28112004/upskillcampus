# Banking Information System

## Overview
The Banking Information System is a simple command-line application that allows users to create bank accounts, deposit and withdraw money, check balances, and view transaction histories. It is implemented in Python and utilizes a JSON file for data persistence.

## Features
- Create a new bank account with an initial deposit
- Deposit money into an existing account
- Withdraw money from an account
- Check account balance
- View transaction history
- Data persistence using a JSON file

## Requirements
- Python 3.x

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/BankingInformationSystem.git
   ```
2. Navigate to the project directory:
   ```sh
   cd BankingInformationSystem
   ```

## Usage
Run the Python script using:
```sh
python BankingInformationSystem.py
```

### Menu Options:
- `1️⃣ Create Account` - Create a new account by entering the account holder's name and an initial deposit.
- `2️⃣ Deposit Money` - Deposit funds into an existing account.
- `3️⃣ Withdraw Money` - Withdraw funds from an existing account.
- `4️⃣ Check Balance` - Display the current account balance.
- `5️⃣ Show Transaction History` - View all past transactions for an account.
- `6️⃣ Exit` - Close the application.

## Data Persistence
The system saves account information in a `accounts.json` file, ensuring data is retained between sessions.

## Example
```
1️⃣ Create Account
Enter Account Holder Name: John
Enter Initial Deposit Amount: 1000
✅ Account created successfully for John
```

## License
This project is open-source and available under the MIT License.

## Author
Your Name

