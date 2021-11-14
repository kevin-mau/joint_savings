# Joint Savings Account with Solidity
 
---
### In this project, we are building smart contracts to automate one of financial institutions’ processes and features - hosting joint savings accounts.  To automate the creation of joint savings accounts, we’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.  We will use the [Remix IDE Website](https://remix.ethereum.org/) to compile and deploy our Smart Contract.  Screenshot demostrations of the Smart Contract interactions will be saved in the `Execution_Results` folder of this repository.  They are also shown below in this `README.md` file.

---
## Installation Guide and Technologies:

Compile, deploy, and interact with the `joint_savings.sol` file in the [Remix IDE Website](https://remix.ethereum.org/).

This application utilizes Solidity.

---
### Setting Accounts:
`Dummy account1 address: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb`

`Dummy account2 address: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0`
 
![set_accounts](https://user-images.githubusercontent.com/85687829/141694412-671295bd-2011-4494-abc3-8b53f0027be3.png)

### Deposit #1 - One Ether (1,000,000,000,000,000,000 Wei):
![deposit1_one_ether](https://user-images.githubusercontent.com/85687829/141699011-fd1449a6-a645-427d-afe5-32aa49c04f97.png)

### Deposit #2 - Ten Ether (10,000,000,000,000,000,000 Wei):
![deposit2_ten_ether](https://user-images.githubusercontent.com/85687829/141699038-473a7ec8-9da3-45b1-b63d-4921dca5435b.png)

### Deposit #3 - Five Ether (5,000,000,000,000,000,000 Wei):
![deposit3_five_ether](https://user-images.githubusercontent.com/85687829/141699052-295a6e4d-6754-4628-b093-daf02af7a58f.png)

### Withdrawal #1 - Five Ether (5,000,000,000,000,000,000 Wei):
![withdrawal1_five_ether_account1](https://user-images.githubusercontent.com/85687829/141699189-468c0f32-5083-42ce-b664-75a08286ca23.png)

### Contract Balance After First Withdrawal:
![last_withdraw_results1](https://user-images.githubusercontent.com/85687829/141699275-91b3cc9e-b708-4455-8b16-7e3b3f50f3b6.png)

### Terminal Output of `lastToWithdraw` of First Withdrawal:
![first_terminal_output_lastToWithdraw](https://user-images.githubusercontent.com/85687829/141699331-56d1faf1-40ab-4623-92e7-52ffc2e575d0.png)

### Terminal Output of `lastWithdrawAmount` of First Withdrawal:
![first_terminal_output_lastWithdrawAmount](https://user-images.githubusercontent.com/85687829/141699344-b1f00294-cf5b-419a-a8aa-7e0c60289bb5.png)

### Withdrawal #2 - Ten Ether (10,000,000,000,000,000,000 Wei):
![withdrawal2_ten_ether_account2](https://user-images.githubusercontent.com/85687829/141699195-403e638f-79b8-480f-9d40-5d3fea5fceaa.png)

### Contract Balance After Second Withdrawal:
![last_withdraw_results2](https://user-images.githubusercontent.com/85687829/141699279-f12ab36b-e5ff-4b27-a498-48c2275b50c3.png)

### Terminal Output of `lastToWithdraw` of Second Withdrawal:
![second_terminal_output_lastToWithdraw](https://user-images.githubusercontent.com/85687829/141699359-442ef476-2629-4468-a494-019a6d5acd6c.png)

### Terminal Output of `lastWithdrawAmount` of Second Withdrawal:
![second_terminal_output_lastWithdrawAmount](https://user-images.githubusercontent.com/85687829/141699364-0e8d1f67-ff91-450e-a54f-1caab3b7aa79.png)


---

## Contributors

kevin-mau

---

## License

MIT
