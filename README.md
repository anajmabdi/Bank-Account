Describe: BankAccount()

Test: "It should store a list of bank accounts."
Code: const account = new BankAccount()
Expected Output: user1, user2, user3

Describe: BankUser()

Test: "It should store the user name and money balance of the account."
Code: const bankUser1 = new BankUser(firstName,LastName,balance)
Expected Output: "John Smith, $3.00";

Describe: addAccount()

Test: "It should add user's account into the list of bank accounts."
Code: account.addAccount(bankUser1)
account;
Expected Output: "John Smith, $3.00"