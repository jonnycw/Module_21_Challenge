# KaseiCoin Token Crowdsale

Module Challenge 21

## Overview

The goal of this project is to create an ERC-20 compliant token and that will be minted by using a `Crowdsale` contract from the OpenZeppelin Solidity library.

The crowdsale contract manages the entire crowdsale process, allowing users to send ether to the contract and in return receive KEI, or KaseiCoin tokens. The contract will mint the tokens automatically and distribute them to buyers in one transaction.

## Technology

This code was written using Solidity 0.5.0 and Remix IDE.

## Evaluation Evidence

1. Compile KaseiCoin token contract

<img width="1503" alt="Compiled_KaseiCoin_contract" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/21ea5a61-810c-4516-8c18-75945696cf35">

2. Compile KaseiCoin crowdsale contract

<img width="1505" alt="Compiled_KaseiCoinCrowdsale" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/0ea9abdb-4311-4e95-bb24-806fb56001d7">

3. Compile KaseiCoin deployer contract

<img width="1505" alt="Complied_KaseiCoinCrodsaleDeployer" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/bde1524a-df24-4ff0-9224-a19569f2e8ce">

4. Deploy the crowdsale contract to a local blockchain using Remix, MetaMask, and Ganache.

<img width="1502" alt="Deploy_Step1" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/8c34b02b-6af0-4b29-8f0e-511f881b7cad">

<img width="1502" alt="Deploy_Step2" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/a9cf9ce2-03ef-462b-88be-df5e4a87da81">

<img width="1503" alt="Deploy_Step3" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/19d8d047-c0b5-433b-b86e-d298a81da4dd">

5. Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances associated with those accounts.

<img width="1505" alt="Buy_Tokens_Step1" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/754f83ea-0b90-417d-a04f-a81cef11deaf">

<img width="1497" alt="Check_Balance_of_Tokens_Bought" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/e05d0cf6-6fba-4eaa-acfe-ad46899d9052">

6. After purchasing tokens with one or more test accounts, view the total supply of minted tokens and the amount of wei that has been raised in the crowdsale contract.

<img width="1507" alt="Check_TotalSupply_WeiRaised" src="https://github.com/jonnycw/Module_21_Challenge/assets/120538932/6fe62ec7-a016-4283-b3a4-536e6c777d41">
