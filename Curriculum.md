 # Beginner: Week 1 JAN 19TH (Intro Day)

## Topic: Introduction to Blockchain Technology & Flow

## Chapter 1: Getting Started with Flow Blockchain

- Lesson 1: Understanding Blockchain Technology
    - Scope, Benefits, and Opportunities

# January 20th
- Lesson 2: Introduction to Flow Blockchain
- Lesson 3: Flow Ecosystem Overview
- Lesson 4: App Custody and Secure User Data Handling
- Lesson 5: Account Linking for Seamless User Experiences
- Lesson 6: Overview of Signature Schemes, Including Multi-signer

   - Commit 1: Explain the difference between a script and a transaction


# Week 2 & 3: JAN 26th - 
## Chapter 2: Introduction to Cadence Language

-  Lesson 1: Overview of Cadence Language
    - Commit 2: 5 Cadence Programming Language Pillars

- Lesson 2: Cadence Data Types and Variables

    - Commit 2: 5 Cadence Programming Language Pillars
    - Commit 3: Deploy the `helloworld` contract with a `greeting` variable and a function called `change-greeting`
    - Commit 4:  Write a script that reads `greeting` and write a transaction that calls `change-greeting` and changes the `greeting` variable
    - Commit 5: Deploy a contract called `Authentication` that defines a profile struct and stores the profile structs in the contract and allows the user to add a new profile



# Intermediate: JAN 27th
## Chapter 3: Understanding Accounts and Transactions

- Lesson 1: Introduction to Accounts and Transactions
- Lesson 2: Handling Transactions in Cadence
- Lesson 3: Managing Accounts

    - Commit 6: Describe a situation where a resource might be better to use than a struct. Can a resource be created in a script or transaction? Assume there isn’t a public function that already exists to create one.
    - Commit 7: Define and deploy your own contract that stores a dictionary of resources. Add a function to get a reference to one of those resources in the dictionary.
    - Commit 8: Tag areas where certain variables can be read. Upload the commit of your answers with this picture.


# Advanced: FEB 2ND
## Chapter 4: Variables and Types in Cadence

Lesson 1: Variables and Constants in Cadence
- Lesson 2: Type System in Cadence
- Lesson 3: Cadence Functions and Control Flow

    - Commit 9: Define a contract that returns a resource that has at least 1 field in it. Then, write 2 transactions:
      - A transaction that first saves the resource to account storage, then loads it out of account storage, logs a field inside the resource, and destroys it.
      - A transaction that first saves the resource to account storage, then borrows a reference to it, and logs a field inside the resource.



# FEB 3RD
## Chapter 5: Writing Your First Cadence Script

- Lesson 1: Functions and Procedures in Cadence
- Lesson 2: Control Flow Statements in Cadence
- Lesson 3: Writing Your First Cadence Script

- Commit 10: Deploy a contract that contains a resource that implements a resource interface. Then, do the following:
      - In a transaction, save the resource to storage and link it to the public with the restrictive interface.
      - Run a script that tries to access a non-exposed field in the resource interface, and see the error pop up.
      - Run the script and access something you CAN read from. Return it from the script.


# Week 4: FEB 9th
## Topic: Smart Contract Development

## Chapter 6: Building Your First Smart Contract

- Lesson 1: Basics of Smart Contracts
- Lesson 2: Creating a Simple Smart Contract
- Lesson 3: Structure and Syntax of Cadence Smart Contracts

# FEB 10th
## Chapter 7: Deploying and Interacting with Smart Contracts

- Lesson 1: Developing with Cadence
- Lesson 2: Writing Your First Smart Contract
- Lesson 3: Deploying and Interacting with Smart Contracts
- Lesson 4: Debugging and Testing in Cadence

     - Commit 11: Deploy your NFT Contract to Testnet. Then, modify the contract as such:
      - Add a new field to the NFT resource that is a Struct of your own choice.
      - Add an Admin resource that is allowed to modify that Struct by running a transaction. No public user should be able to change this Struct.


# Week 5: FEB 16th
## Topic: Decentralized Application (DApp) Development

## Chapter 8: DApp Development on Flow

- Lesson 1: Introduction to DApps
- Lesson 2: Understanding Decentralized Applications (DApps)
- How to build: DeFi Platform, Gaming, NFT Marketplaces, DAO system, etc. 
- Lesson 3: Building User Interfaces for DApps

# FEB 17TH
## Chapter 9: Smart Contract Integration in DApps

- Lesson 1: Connecting Smart Contracts and DApps
- Lesson 2: User Authentication in DApps
- Lesson 3: Data Storage and Retrieval

# Week 6: FEB 23RD
## Chapter 10: Integrating Smart Contracts with DApps

- Lesson 1: Connecting Smart Contracts and DApps (continued)
- Lesson 2: User Interfaces for DApps (continued)
- Lesson 3: Testing and Debugging DApps

     - Commit 12: Add FLOAT receiver to your wallet. Add your wallet address to receive the certificate following the submission of commits.

