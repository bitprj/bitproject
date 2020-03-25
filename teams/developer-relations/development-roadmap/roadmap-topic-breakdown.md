# Roadmap Topic Breakdown

## Topic: Python

**Module: Intermediate Python**

_**Learning Objectives**_

* Students will continue applying their fundamental Python skills learned from the previous module.
* Students will begin learning about how to integrate basic data structures like lists and dictionaries to add complexity to their Python code.
* Students will learn how they can use for/while loops and if statements to control the flow of their code.
* Students will learn how to represent strings in Python using F-strings.

_**Activities**_

* Bookkeeper
  * You will write a program that reads and parses a list of Dewey decimal numbers and match it to the correct genre based on the number and then find the distribution of each genre.
* Creating a Menu
  * You will write a simple menu program which prints a menu and behaves according to user input.
* Message Cipher
  * Encode user input with both a Caesar Cipher and a Symmetric Cipher.

_**Labs**_

* Word Translation Calculator
  * You are going to write a program that calculates how often a word appears in a given string.
* Basic Calculator
  * Create a functional calculator in python that can do simple arithmetic operations on two numbers.
* Tic-Tac-Toe
  * Write a Tic-Tac-Toe game, and you will play against an AI which chooses random moves.

## Topic: APIs

**Module: API Concepts**

_**Learning Objectives**_

* Students will learn the basic concepts behind APIs, why they are used, the idea behind their functionality, etc
* Students will understand CRUD operations
* Students will learn HTTP Methods and Endpoints
* Students will understand JSON data 

_**Activities**_

* Introduction to APIs
  * Introduce what an API is, possibly ask students to come up with their own possible uses of APIs, introduce vocabulary like client and server, etc. 
* CRUD Notes App
  * Students will learn how to use CRUD operations through a basic concrete example such as a notes app
* RESTful APIs
  * Students will learn what you need to make a basic HTTP request: Url, Method, Headers, and Body as well as a basic HTTP response: status code, headers, and body 
* Pizzeria
  * Students will learn data formatting with JSon; keys and values through examples such as a pizza order and how to use these formats with HTTP
* Security
  * Students will learn how to use authentication for apis such as API keys

_**Labs**_

* Weather Application
  * students will use a simple weather API to create a weather app. They can use their basic knowledge of HTML/CSS and other backend resources
* Notes Application
  * similar to weather application lab, but instead students can create an application to keep notes on

_\*\*\*\*_

### Module: Testing APIs with Postman

_**Learning Objectives**_

* Students will learn how to use Postman in order to test API requests and why this is useful to developers
* Understand Postman Collections and Collection Runner
* Understand Postman Mock Servers
* Learn Postman Documentation

_**Activities**_

* Creating and Testing BitBloxs
  * Use the bitblox API in order to teach students the basics of how to run requests through postman
* Creating Postman Collections
  * Teach students how to create collections, import collections, and create documentation. 
* Collection Runners
  * Students will learn how to use the postman collection runner, either through bitblocks or through a new API
* Mock Servers
  * Student can learn about postman's Mock Servers and why they are useful
* Documentation in Postman
  * Teach students how to make documentation in postman

_**Labs**_

* NASA API
  * Adjust the activity APIs for front end developers in order to create a lab where students create a more indepth website using NASA's API
* BitBloxs
  * Use Postman to play the bitbloxs game

## Topic: Blockchain

**Module: Principles of Blockchain**

_**Learning Objectives**_

* Students will learn about what distinguishes a blockchain from existing technologies
* Students will learn about the Bitcoin architecture and its defining success as well as failures
* Students will learn about Post-Bitcoin architectures
* Students will learn about what Smart Contracts and are and their uses

_**Activities**_

* Hash Playground 
  * Experiment with different hashing protocols used in different blockchain architectures
* Public/Private Key Cryptography 
  * Walk through a Public-Private Key encryption scenario
* PoW Blockchain 
  * Create a simple Proof of Work \(PoW\) based blockchain
* PoS Blockchain 
  * Create a simple Proof of State \(PoS\) based blockchain

_**Labs**_

* Your Own PoW Blockchain 
  * Create an upgraded PoW blockchain
* Your Own PoS Blockchain 
  * Create a custom staking protocol

**Module: Fundamental Solidity**

_**Learning Objectives**_

* Students will learn about the Ethereum Blockchain architecture and how it executes Smart Contracts
* Students will learn about the general procedure for developing, deploying, and testing smart contracts
* Students will learn about fundamental types and their associated operations in Solidity

_**Activities**_

* Ethereum Simulation
  * Learn to send, receive, and analyze transactions in a simulated environment
* Hello World 
  * Launch, Deploy, and Interact with a simple contract
* Repeat after Me
  * Store and Retrieve Data from a Smart Contract
* Solidity Oddity
  * Experiment with solidity-specific data types and understand their uses

_**Labs**_

* Blockulator
  * Create a smart contract calculator that can perform simple arithmetic on integers
* Cipher
  * Create a smart contract with an encryption and decryption utility utilizing solidity-specific data types

**Module: Intermediate Solidity**

_**Learning Objectives**_

* Students will gain mastery of the Ethereum memory layout
* Students will be introduce to compound and reference types
* Students will learn about the mainstream applications of the Ethereum blockchain

_**Activities**_

* Voting
  * Create a simple voting smart contract where individuals can cast votes which are then tallied
* Token
  * Launch a token that can be transferred among Ethereum network users
* Blind Auction
  * Create a smart contract for a blind auction on a certain goods

_**Labs**_

* Rolodex
  * Create a smart contract that stores contact information and preferences of individuals
* Token 2.0
  * Upgrade the original Token implementation for more fine-grained control and advanced features

**Module: Advanced Solidity**

_**Learning Objectives**_

* Students will learn about using libraries to promote code reusability
* Students will learn about how to use multiple contracts together to build more complex applications
* Students will learn about unit testing to ensure safe contract design

_**Activities**_

* MathLib
  * Create a library for faster and safer math operations
* Contract-to-Contract
  * Deploy two contracts and walk through the process of invoking functions from one through the other
* Lead Zeppelin
  * Walk through using existing libraries like OpenZeppelin to make developing contracts faster and safer
* Test Driven Development
  * Learn to leverage unit testing to ensure proper smart contract behavior

_**Labs**_

* Telephone 
  * Have several contracts relay data to each other, mutating and deciphering data in a predictable fashion 
* Zeppelin Tokens
  * Use OpenZeppelin to create Tokens and subject them to unit tests

**Module: Alternative Blockchains**

_**Learning Objectives**_

* Students will learn about alternative blockchain platforms that support the Solidity Programming Language
* Students will learn about alternative blockchain platforms that use a language other than Solidity
* Students will learn about permissioned blockchain platforms as well as the benefits and drawbacks they provide

_**Activities**_

* TRON
  * Deploy and interact with a contract on the TRON platform
* EOS
  * Deploy and interact with a contract on the EOS platform
* HyperLedger
  * Deploy and interact with a contract on the Hyperledger platform

_**Labs**_

* TRON Port 
  * Deploy the previously built calculator app onto the TRON platform
* EOS Calculator
  * Port the calculator you built in Solidity to EOS

**Module: Beyond Blockchain**

_**Learning Objectives**_

* Students will learn about how to create cross-blockchain applications
* Students will learn about decentralized storage protocols and their interface to smart contracts
* Students will learn about the applications of Blockchain for Internet-of-Things \(IoT\) devices

_**Activities**_

* Aboard the Ark
  * Create two contracts on two separate blockchain platforms and make them interact with each other
* IPFS x Infura 
  * Store large amounts of data in a decentralized fashion
* Iota
  * Experiment with a blockchain for Internet of Things \(IoT\) devices

_**Labs**_

* IPFS x Ethereum
  * Use IPFS with Ethereum to easily store and retrieve arbitrary files

