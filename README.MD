# Flow Vending Machine

## A tutorial to understand smart contracts #onFlow and getting started with Cadence

What's a Smart Contract? The most common used analogy for explaining Smart Contracs is a vending machine. A smart contract is a piece of software (run on a blockchain) that allows anyone to interact with it under certain rules. When a vending machine's owner deploys it on the street, they leave it there under a implicit *contract*, "if you deposit here a buck, I'll give you a soda in exchange". This is what you'll acommplish with a Smart Contract, deploy your contract on an *Account* (more on this latter) and anyone would be able to interactuate with it in the ways you have established through your code. This tutorial will walk you through learning cadence while building a contract that emulates exactly that, a vending machine! Before taking this tutorial make sure you have completed the cadence tutorial [https://docs.onflow.org/cadence/tutorial/01-first-steps] as we will be revisiting some concepts but we may use some other advanced concepts soon.
(playground tutorial + final solution for each point on github?)

## Table of contents
1. [Basic concepts review: smart contracts #onFlow arquitecture and resource oriented programming](#basic-concepts)
1. [Defining your products](#products)
1. [Creating your vending machine](#vending-machine-contract)
1. [Delivering products through your vending machine] (#delivering-products)
1. [Getting paid for your products] (#getting-paid)
1. [Retrieving your earns] (#retrieving-your-earns)
1. [Authorizing employees to collect the money] (#authorize-other-to-retrieve-your-earns)
1. [TO-DO (better) Creating scarcity and filling the machine] (#filling-the-machine)
1. [TO-DO Contract interface for vending machines for different kinds of vending machines?, NFT vending machine (gacha)]

## Basic concepts
### Accounts
### Transactions and scripts
### Resource-oriented programming
## Products
(creating a couple of resources that will represent our vending products)
## Vending Machine Contract
(creating the basic structure for the vending machine contract. To define: contract == machine?? contract creates machine resources?)
## Delivering products
(including functions and capabilities for anyone to be able to get a product resource from the contract)
## Getting paid
(introducing a flow token vault in the contract? in the machine resource? that will keep the funds that will be passed to the sellProduct(): @Product method)
## Retrieving your earns
(private capability for withdrawing funds from the machine's vault)
## Authorize other to retrieve your earns
(creation of a "EmployeeKey/Card" resource that will hold a capability field for beeing able to deposit to the funds in the main vault, this resource will also allow the next point...)
## Filling the machine
(related to the contract-machine or resource-machine, how to explain the creation of resources in a smoother way? First approach delivering infinite producst for latter explaining minting and artificial scarcity? This could be easily just after delivering products and latter add a further point on how to have a delegated "employee resource" that can mint products)
## TODO
(introduce the concept of contract interfaces by abstracting the behaviour of the vending machine to a vending contract interface. Adapt the vending machine contract to this approach. Make a gacha vending machine that distributes NFTs instead of random resources)