# Compensation Management through Solidity 

## Contract Addresses Deployed on Kovan Testnet
AssociateProfitSplitter:  0x79EAE45534Ad7fC31E66cC9A82c3F25B7a48Afa9  
TieredProfitSplitter:  0xB3CF40da13685f70Da815F1Ac3F7B8e47D913e4A  
DeferredEquityPlan:  0xcc386992C3Ef57e18aC36B68962F757cfdcf9617

## Objective
* Create Smart Contracts to Dynamically Manage Confirmation Plans for Multiple Tiers of Employees
* Using Solidity, these contracts are deployed on an the company's Ethereum Blockchain

### AssociateProfitSplitter contract:
* Evenly splits Ether payouts to associate-level employees
* Allows HR to pay these employees efficiently and quickly

### TieredProfitSplitter contract:
* Enables to tier Ether payouts automatically based on the employee's position in the company
* The contract was initially coded to pay the CEO 60%, the CTO 25% and another employee, Bob, 15%

### DeferredEquityPlan contract:
* Automates the distribution of company shares for employees participating in a company deferred equity incentive plan
* The contract was initially coded to manage 1000 share awards to annually distribute 250 shares over 4 years for one employee

#### Note
* Please see .sol files in the Contract_Codes folder in this repo for individual contract codes
