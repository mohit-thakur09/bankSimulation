# Bank Simulation System

The **Bank Simulation System** is a Python project designed to simulate the operations of a bank. It utilizes various Python modules such as `math` for arithmetic calculations, `random` for generating unique account numbers, and `datetime` for auditing logs of withdrawals and credits. This system provides a user-friendly interface for opening accounts, checking account details, withdrawing money, crediting money, and even closing accounts. Additionally, a bank manager can use the system to access information about all bank account users.

## Features

### User Operations

1. **Open Account**:
   - Users can open an account with a programmatically generated unique account number.
   - Provide personal details such as name, initial deposit, and contact information.

2. **Check Bank Account Details**:
   - Users can check their bank account details, including the account number, balance, and transaction history.

3. **Withdraw Money**:
   - Perform withdrawals from your bank account.
   - The system records the transaction in the transaction history.

4. **Credit Money**:
   - Deposit money into your bank account.
   - The system records the transaction in the transaction history.

5. **Close Account**:
   - Close your bank account if needed.

### Manager Operations

1. **Check All Bank Account Users**:
   - Bank managers can access information about all bank account users.
   - This provides an overview of the bank's clientele.

## Getting Started

To run the Bank Simulation System, follow these steps:

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the main Python script:

   ```bash
   python bank_simulation.py
   ```

4. Follow the on-screen instructions to perform various banking operations.

## Usage

### User Operations

1. **Open Account**:
   - Provide your name, initial deposit, and contact information to open an account.

2. **Check Bank Account Details**:
   - Enter your account number to view your account details and transaction history.

3. **Withdraw Money**:
   - Enter the withdrawal amount to deduct from your account balance.

4. **Credit Money**:
   - Enter the deposit amount to add to your account balance.

5. **Close Account**:
   - Close your account if you wish.

### Manager Operations

1. **Check All Bank Account Users**:
   - Managers can view the list of all bank account users, including their account numbers and balances.

## Project Structure

- `bank_simulation.py`: The main Python script for the Bank Simulation System.
- `bank.py`: Contains functions and classes for managing bank accounts, transactions, and user interactions.
- `accounts/`: Stores user account information and transaction logs in separate CSV files.
- `assets/`: Contains images, logos, or other assets used in the project.

## Contributing

Contributions to this project are welcome. You can contribute by opening issues, providing feedback, or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Enjoy using the Bank Simulation System for your banking needs! 💰🏦
