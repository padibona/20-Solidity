# Unit 20 - "Joint Savings Account"

![alt=“”](Images/20-5-challenge-image.png)

### Background

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

### Files

[Joint Savings Smart Contract File](Starter_Code/joint_savings.sol)

[Folder with screenshots](Execution_Results)

### accountOne Address: 
0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb 
### accountTwo Address:
0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0

### Screenshots of contract deployment and interactions

* Note - for the last 2 withdraw transactions I took one screenshot for each one which showed the contractBalance, 
lastToWithdraw and the lastWithdrawAmount functions after I executed them, so I only have 6 pictures.

Transaction 1 - setAccounts:
![alt=“setAccounts”](Execution_Results/1_setAccounts.png)
Transaction 2 - deposit 1 Ether as Wei:
![alt=“setAccounts”](Execution_Results/2-1_1eth_as_wei.png)
Transaction 3 - deposit 10 Ether as Wei:
![alt=“setAccounts”](Execution_Results/2-2_10eth_as_wei.png)
Transaction 4 - deposit 5 Ether:
![alt=“setAccounts”](Execution_Results/2-3_5eth.png)
Transaction 5 - withdraw 5 Ether into accountOne:
![alt=“setAccounts”](Execution_Results/3-1_5eth_to_accountOne.png)
Transaction 6 - withdraw 10 Ether into accountTwo:
![alt=“setAccounts”](Execution_Results/3-2_10eth_to_accountTwo.png)