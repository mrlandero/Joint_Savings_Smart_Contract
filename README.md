# Joint_Savings_Smart_Contract
Create a joint savings account via a smart contract in Solidity, deploy the contract, and interact with the functions to complete transactions.

---

## Technologies

This project leverages solidity 0.5.0 with the following packages:

We don't have any packages to use. The only platform we need for this program is the Remix IDE website. We'll be able to write and run our code from the Remix IDE without using any additional libraries or dependencies. 

---

## Installation Guide

As mentioned in our `Technologies` section above, we don't have any libraries or dependencies to install. We will use the Remix IDE to code, deploy, and interact with our Smart Contract. 
To use the Remix IDE, click on the link below:

**[Remix IDE](https://remix.ethereum.org/)**

---

## Usage

To use the 'Joint_Savings_Smart_Contract' application, simply clone the repository, open the file `joint_savings.sol` in the Remix IDE, and deploy via the Javascript Virtual Machine.

Once the contract is deployed, interact with the contract by using the sidebar. You will see the functions that we have created in our contract. 

Step 1: Deploy Contract
Once the Solidity Smart Contract is compiled, we have to deploy it in order to interact with it:

![Deploy Contract](Execution_Results/one_deploy_contract.png)

We can see in the preceding image that once the contract is deployed, you can verify its deployment in one of two ways. First, below the `Deploy` button, you will find a tab labeled `Deployed Contracts`. Once you click on this tab, you will see the smart contract you deployed, along with all of the interactive functions for that contract. 
Furthermore, we can see the successful deployment of the contract below our code, in what we call the `terminal` view. 

Great! Now that we have deployed our contract, let's start interacting with it. 

Step 2: Set Accounts
Use the `setAccounts` function, found in the interactive contract section in our sidebar, to assign adresses for both accounts in the `JointSavings` contract:

![Set Accounts](Execution_Results/two_set_accounts.png)

In the preceding image we can see the interaction taking place with our sidebar `setAccounts` function. In the `terminal` view, we can see the successful transaction execution, along with the confirmation that the addresses have been assigned. 

Step 3: Deposit 1 Ether
Use the `deposit` function, found in the interactive section in our sidebar, to deposit 1 ether into the contract:

![Deposit 1 Ether](Execution_Results/three_deposit_1_ether.png)

In the `Value` input box, type in 1 Ether, and then click on the `Deposit` function button. (You can also deposit as wei. The equivalent is 1000000000000000000 wei to 1 ether). Once the transaction is complete, you should receive a successful transaction message in the `terminal` view, along with the transaction information. 
