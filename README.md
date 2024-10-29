Fake Product Identification
This project is a blockchain-based application designed to verify product authenticity by recording transactions on the blockchain. It uses smart contracts written in Solidity to maintain product details and validate sellers, ensuring that only genuine products are recorded and tracked.

Project Structure
Contracts: Smart contracts are located in the contracts folder, with key contracts including product.sol and Migrations.sol.
Migrations: Scripts to deploy the smart contracts are in the migrations folder.
Build: Compiled contract artifacts are stored in the build/contracts folder.
Frontend: HTML files such as addProduct.html and addSeller.html provide a user interface for adding and verifying products and sellers.
Technologies Used
Blockchain: Ethereum blockchain, Truffle, Ganache
Smart Contracts: Solidity
Frontend: HTML, JavaScript
Backend: Node.js (for server-side logic and integration with Truffle)

Prerequisites
Node.js (latest version)
Truffle Framework (npm install -g truffle)
Ganache (for local Ethereum blockchain simulation)

Setup and Installation

Clone the Repository use following 
https://github.com/priyankamane7/Fake-product-detection-using-Blockchain.git
cd Fake-Product-Identification

Install Dependencies
npm install

Run Ganache
Start Ganache to create a local Ethereum blockchain network.

Compile Contracts
truffle compile

Deploy Contracts
truffle migrate

Running the Application
Start the development server:
npm start

Open addProduct.html or addSeller.html in your browser to interact with the application.
