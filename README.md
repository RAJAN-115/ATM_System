# 🎉 ATM Mini Project 🎉



Welcome to the ATM Mini Project! This C++ project simulates a basic ATM system with interactive features.

## 🚀 Getting Started

### 1. Clone the Repository

To get started, clone the repository to your local machine:


git clone https://github.com/yourusername/your-repo.git


Replace `yourusername` and `your-repo` with your GitHub username and repository name.



### 2. Open in VS Code

Open the project in Visual Studio Code:

cd your-repo
code .

Ensure VS Code is installed. This command opens the entire project folder in VS Code



### 3. Open in Notepad

To open the project in Notepad:

Navigate to the project folder.
Right-click on `atm.cpp`.
Select "Open with" → "Notepad".



### 4. Compile the Code

Compile the code using a C++ compiler:

g++ atm.cpp -o atm


This compiles `atm.cpp` and creates an executable file named `atm`.



### 5. Run the Program

Run the compiled executable:

./atm


On Windows, use `atm.exe` instead of `./atm`.



🛠️ Features
================

### 1️⃣ Check Balance

🔍 View your current account balance.

### 2️⃣ Cash Withdraw

💸 Withdraw cash from your account.

### 3️⃣ Show User Details

📝 Display account details including name and mobile number.

### 4️⃣ Update Mobile No.

📞 Change your registered mobile number.

🧩 Code Explanation
=====================

### ATM Class

#### Private Members

* `account_No` 📦: Stores the account number.
* `name` 🏷️: Stores the account holder's name.
* `PIN` 🔒: Stores the account PIN.
* `balance` 💰: Stores the account balance.
* `mobile_No` 📱: Stores the mobile number.

#### Public Functions

* `setData(long int account_No_a, string name_a, int PIN_a, double balance_a, string mobile_No_a)` 📝: Initializes user data.
* `getAccountNo()` 🔢: Returns the account number.
* `getName()` 🧑: Returns the account holder's name.
* `getPIN()` 🔑: Returns the PIN.
* `getBalance()` 💵: Returns the current balance.
* `getMobileNo()` 📞: Returns the mobile number.
* `setMobile(string mob_prev, string mob_new)` 🔄: Updates the mobile number if the old one matches.
* `cashWithDraw(int amount_a)` 💸: Allows withdrawal of cash if valid and sufficient balance is available.

### Main Function

#### User Authentication

🔑 Prompts for account number and PIN. Validates these details.

#### Menu Options

📋:

1. Check Balance: Shows the balance.
2. Cash Withdraw: Withdraws cash.
3. Show User Details: Displays user details.
4. Update Mobile No.: Updates mobile number.
5. Exit: Exits the application.

### Notes

* `_getch()` 🕹️: Pauses the screen until a key is pressed. If `conio.h` is unavailable, use another method.

📬 Contact
================

For questions or suggestions, feel free to reach out:

Email: [rajanrp115@gmail.com](mailto:rajanrp115@gmail.com) ✉️
GitHub: [RAJAN-115](https://github.com/RAJAN-115) 🌟
