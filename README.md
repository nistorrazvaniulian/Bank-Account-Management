# Bank Account Management

This Java application is a simple bank account management system that reads account information from a .txt file and performs basic banking operations such as deposit, withdrawal, and balance inquiry.

## Features

- Supports two types of accounts: Savings and Checking
- Reads account information from a .txt file
- Generates unique account numbers for each account
- Calculates interest rates based on account type
- Provides features specific to each account type (e.g., debit card details for Checking accounts, safety deposit box details for Savings accounts)
- Allows basic banking operations such as deposit, withdrawal, transfer, and balance inquiry

## Installation

To run this application, you need Java installed on your system.

1. Clone this repository:
   ```bash
   git clone https://github.com/nistorrazvaniulian/Bank-Account-Management.git

2. Navigate to the project directory:
    ```bash
    cd Bank-Account-Management

3. Compile the Java files:
   ```bash
   javac Main.java

4. Run the application:
   ```bash
   java Main

## Usage

1. Prepare a .txt file containing account information in the following format: `name, SSN, accountType, initialDeposit`.

2. Make sure the .txt file path is correctly set in the `Main.java` file.

3. Run the application as instructed in the Installation section.

4. Follow the prompts to perform various banking operations.

## Sample .txt File

A sample .txt file (`bank.txt`) might look like this:

John Doe,123456789,Savings,1000
Jane Smith,987654321,Checking,1500

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request.



