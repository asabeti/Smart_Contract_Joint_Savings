# UW FinTech BootCamp Module 20 Challenge - Smart Contract Joint Savings Account

---

## Description
A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, 
Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate 
many of the institutions’ financial processes and features, such as hosting joint savings accounts. 
The steps for this project are divided into the following sections:

* Using Solidity, create a smart contract that serves as a Joint Savings Account between two Ethereum Addresses.
  * It should function so that users are able to deposit, withdraw, set each account address, and validate that the correct addresses are used when calling the contract functions.
* Compile and Deploy Your Contract using the Remix VM. 
* Interact with Your Deployed Smart Contract.
  * Test the deposit functionality of your smart contract by making 3 seperate deposits. Take screenshots of each transaction.
  * Test the withdrawal functionality of your smart contract by making 2 separate withdrawals. Take screenshots of each transaction. 

---

## Summary
Using [Remix](https://remix-project.org/), the smart contract can be compiled into an Ethereum VM (Remix VM in this case). After all the required functions are coded and the contract is successfully compiled and deployed -- it should look like this:

![Screenshot of initial contract on Remix UI with setAccounts, withdraw, contractBalance, lastToWithdraw, and lastWithdraw functions](https://github.com/asabeti/Module_20_Smart_Contract_Joint_Savings/blob/main/Execution_Results/Set%20Accounts%20Step%201.png)

Using the `deposit` function in Remix will fund the savings account.
To test our deposit function, we will make 3 separate deposits.
  * Transaction 1: Deposit 1 Ether as Wei.
  ![Deposit one](https://github.com/asabeti/Module_20_Smart_Contract_Joint_Savings/blob/main/Execution_Results/Transaction%201.png)
  * Transaction 2: Deposit 10 Ether as Wei.
  ![Deposit two](https://github.com/asabeti/Module_20_Smart_Contract_Joint_Savings/blob/main/Execution_Results/Transaction%202.png)
  * Transaction 3: Deposit 5 Ether.
  ![Deposit three](https://github.com/asabeti/Module_20_Smart_Contract_Joint_Savings/blob/main/Execution_Results/Transaction%203.png)






