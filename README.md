# Udacity_Ethereum_DAPP_SCM_Project
This project is from the Udacity Blockchain Developer Nanodegree - Project: Ethereum Dapp for Tracking Items through Supply Chain

### Getting Started
1. Clone the project: <br>
`$ git clone https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project.git`

2. Cd into project directory: <br>
`$ cd Udacity_Ethereum_DAPP_SCM_Project`

3. From the  project parent directory install dependencies: <br>
`$ npm install`

4. Launch ganache GUI

5. Compile and migrate contract <br>
`$ truffle compile` <br>
`$ truffle migrate --reset` <br>

6. Test the contract <br>
`$ truffle test`

7. In a separate terminal window, launch the DApp <br>
`$ npm run dev`


### Program Versions
1. <b>Truffle v5.11.5 (core: 5.11.5)</b> <br>
Truffle is a development framework for Ethereum that simplifies the process of building, testing, and deploying smart contracts.

2. <b>Ganache v7.9.1</b> <br>
Ganache is a personal blockchain for Ethereum development, providing a local testing environment with configurable settings for testing smart contracts.

3. <b>Solidity - 0.8.0 (solc-js)</b> <br>
Solidity is a programming language for writing smart contracts on the Ethereum blockchain, and solc-js is the Solidity compiler for JavaScript, used to compile Solidity code into bytecode.

4. <b>Node v20.9.0</b> <br>
Node.js is a JavaScript runtime that allows developers to execute server-side JavaScript code. It is commonly used in Ethereum development for running server-side scripts and tools.

5. <b>Web3.js v1.10.0</b> <br>
Web3.js is a JavaScript library that provides an interface for interacting with the Ethereum blockchain. It allows developers to build decentralized applications (DApps) by connecting to Ethereum nodes and sending transactions or reading data from the blockchain.

### Contract Information
1. Contract Address on the Goerli Network: `0x18b9051f96BC56FCb9F6F1D1FC6Be86eaCCdB276`
2. Transaction Hash that deployed the contract on Goerli: `0x516af3d38ee1163e698870df1b2ab564b4db6dae3ff822188985313f44f81b70`

The transaction log can be seen here: https://goerli.etherscan.io/address/0x18b9051f96BC56FCb9F6F1D1FC6Be86eaCCdB276

### UML Diagrams
Note: I have built the code with below considerations as mentioned in project requirements:
1. Farmer: Harvest, Process, Pack, PutForSale, Ship
2. Disturbitor: Buy
3. Retailer: Receive
4. Consumer: Purchase

#### Activity Diagram
![activity_diagram](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/c7fe0224-e7e0-46d5-b6a4-a91686a7a68b)

#### Sequence Diagram
![sequence_diagram](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/ee39a124-accd-4d17-84cd-6820b7940e36)

#### State Diagram
![state_diagram](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/663fd44c-f0b7-442c-b30e-595efd6b2e91)

#### Class Diagram
![class_diagram](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/29e2cfae-9bbe-4b0f-b61a-925d977345dd)


### UI screenshots
These screenshots are taken after performing all 8 actions. All actions are performed from the same metamask address for simplicity purpose.

![product_overview](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/ce7566d5-5fd1-43f1-8464-6bce9813dc7e)
![farm_details](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/0a4a098c-cc6f-4cae-8275-c827bd08b72e)
![product_details](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/41423e99-880c-4bd5-bb38-dc458694846a)
![transaction_history](https://github.com/anishsamant/Udacity_Ethereum_DAPP_SCM_Project/assets/21247634/e1709f31-d302-419e-8c08-605c08ca1cc8)

