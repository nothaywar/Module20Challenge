# Module20Challenge
# Joint Savings Smart Contract

The Joint Savings contract allows two users to create a joint savings account on the Ethereum blockchain. The contract includes functionalities to deposit ether into the contract, set two addresses that will have withdrawal privileges, and facilitate withdrawals by these authorized accounts.

## Functionality:

- **Deploy Contract**: Allows users to deploy the joint savings contract on the Ethereum blockchain.
  
- **Deposit Ether**: Any users can send ether to the smart contract. The contract tracks the total balance.

- **Set Accounts**: Two addresses can be designated as authorized accounts, which are permitted to withdraw funds.

- **Withdraw Funds**: Authorized accounts can withdraw a specified amount of ether from the contract. If a non-authorized account tries to withdraw funds, the transaction will fail.

## Testing:

The contract has been tested and verified on a local blockchain environment using the Remix IDE. Screenshots of each significant step are provided:

1. **Deploying the Contract**: 
   ![Deploy Contract](Execution_Results/deploy%20contract.png)

2. **Depositing Ether**:
   ![Deposit Ether](Execution_Results/deposit%20eth.png)

3. **Setting Authorized Accounts**:
   ![Set Accounts](Execution_Results/set%20accounts.png)

4. **Attempt to Withdraw from a Non-Authorized Account**:
   ![Withdraw from Non-Owner](Execution_Results/withdraw%20from%20non-owner.png)

5. **Withdraw from an Authorized Account**:
   ![Withdraw from Owner](Execution_Results/withdraw%20from%20owner.png)
