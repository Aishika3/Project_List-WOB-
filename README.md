# Project_List-WOB-
Project lists for WOB

# 1.Verification Document Project Overview:

The Verification Document Project is a blockchain-based model designed to facilitate document verification. It offers the capability to verify documents by exporting them as PDF files when required. Additionally, the system employs QR codes for verification purposes.

**Technologies Used:**
- React.js: A JavaScript library for building user interfaces.
- Bootstrap: A front-end framework for designing responsive and mobile-first websites.
- jQuery: A fast, small, and feature-rich JavaScript library.
- Metamask: A crypto wallet and gateway to blockchain apps.
- Web3.js: A JavaScript library for interacting with the Ethereum blockchain.
- ipfs.js: A JavaScript implementation of the InterPlanetary File System (IPFS), utilizing the SHA-256 algorithm for hashing.
- aos lib: Animate on Scroll library for adding animations to web pages.
- Ethereum Testnet: A network environment for testing Ethereum-based decentralized applications (DApps).
- Polygon (formerly Matic Network): A layer 2 scaling solution for Ethereum.

**Key Features:**
1. **Document Verification:** Users can verify documents securely using blockchain technology.
2. **PDF Export:** Documents can be exported as PDF files for convenience and accessibility.
3. **QR Code Verification:** The system utilizes QR codes for quick and reliable document verification.
4. **Integration with Metamask:** Metamask integration enables seamless interaction with the Ethereum blockchain.
5. **IPFS for File Storage:** IPFS is used for decentralized file storage, ensuring data integrity and availability.
6. **Animated UI Elements:** AOS library is implemented to add visually appealing animations to the user interface.
7. **Blockchain Testing:** Ethereum Testnet and Polygon are utilized for testing blockchain functionalities in a controlled environment.

**Implementation Details:**
- React.js is used for building the front-end interface, providing a dynamic and interactive user experience.
- Bootstrap ensures responsiveness and consistent design across different devices and screen sizes.
- jQuery enhances the user interface with dynamic content and smooth interactions.
- Metamask integration enables secure interactions with the Ethereum blockchain and facilitates wallet management.
- Web3.js is utilized for connecting and interacting with smart contracts deployed on the Ethereum network.
- ipfs.js implements IPFS functionality, allowing for decentralized and resilient file storage.
- Ethereum Testnet and Polygon serve as testing environments for blockchain-related features, ensuring stability and security.

**Conclusion:**
The Verification Document Project offers a robust solution for document verification, leveraging blockchain technology to ensure security, reliability, and accessibility. With features like PDF export, QR code 
verification, and seamless blockchain integration, it provides a user-friendly experience while maintaining data integrity and confidentiality.


# 2.Restaurant Review Management System

**Overview:**
The Restaurant Review Management System is a Solana-based program designed to facilitate the management of restaurant reviews. Users can add new reviews and update existing ones, with all review data stored securely on the Solana blockchain. The system includes a simple React frontend for easy interaction with the blockchain.

**Features:**
1. **Add Reviews:** Users can submit new reviews for restaurants, including ratings and descriptions.
2. **Update Reviews:** Existing reviews can be updated with revised ratings or descriptions.
3. **On-Chain Storage:** All review data is stored securely on the Solana blockchain, ensuring transparency and immutability.
4. **Basic Frontend:** A basic React frontend provides users with an intuitive interface for interacting with the blockchain and managing reviews.

**Technologies Used:**
- Solana: A high-performance blockchain platform for decentralized applications.
- React: A JavaScript library for building user interfaces.
- Solana SDK: The Solana Software Development Kit for building Solana programs.
- React Router: A library for routing in React applications.
- Solana Wallet: A digital wallet for managing Solana tokens and interacting with the Solana blockchain.

**How to Use:**
1. **Add Reviews:** Users can submit new reviews by providing ratings and descriptions for restaurants.
2. **Update Reviews:** Existing reviews can be updated with revised ratings or descriptions as needed.
3. **View Reviews:** The frontend allows users to view existing reviews for different restaurants.
4. **Interact with Blockchain:** Users can interact with the Solana blockchain directly through the frontend to manage reviews securely.

**Conclusion:**
The Restaurant Review Management System provides a convenient and secure way to manage restaurant reviews using blockchain technology. With features for adding, updating, and viewing reviews, along with on-chain storage for data integrity, it offers a reliable solution for restaurant owners and customers alike.

3.### Project Description:
The project aims to create a DApp that allows users to lock funds for a specified duration using smart contracts deployed on the Ethereum blockchain. Once the lock period expires, users can withdraw their locked funds. This functionality can be useful for various purposes such as time-locked savings, token vesting schedules, or other time-dependent operations.

### Technology Stack:
1. **Ethereum Blockchain**: The decentralized platform where the smart contracts are deployed and executed. Ethereum provides the infrastructure for decentralized applications and smart contracts.

2. **Solidity**: The programming language used to write smart contracts for the Ethereum blockchain. Solidity is specifically designed for creating contracts and executing them on the Ethereum Virtual Machine (EVM).

3. **Hardhat**: Hardhat is a popular development environment for Ethereum smart contracts. It provides a wide range of tools for compiling, testing, debugging, and deploying smart contracts. In this project, Hardhat is used for contract deployment, testing, and scripting.

4. **Chai**: Chai is a testing framework for JavaScript applications. In this project, it's used for writing unit tests for the smart contracts to ensure their correctness and functionality.

5. **Hardhat-Toolbox**: Hardhat-Toolbox is a collection of utilities and helpers for Ethereum development with Hardhat. It includes tools for network management, time manipulation in tests, and other helpful functions.

6. **Node.js**: Node.js is a JavaScript runtime environment that allows running JavaScript code outside of a web browser. In this project, it's used for scripting, running tests, and managing dependencies.

7. **Nomic Labs Tooling**: Specifically, `@nomicfoundation/hardhat-toolbox` and `@nomicfoundation/hardhat-chai-matchers/withArgs` are used for additional utilities and matchers to enhance testing capabilities in Hardhat.

### Workflow:
1. **Contract Development**: Smart contracts are written in Solidity to define the locking and withdrawing functionality.

2. **Testing**: Unit tests are written using Chai to ensure that the smart contracts behave as expected under different scenarios. Hardhat is used to run these tests and provide a test environment.

3. **Deployment**: Hardhat is utilized to deploy the smart contracts onto an Ethereum network, either a testnet or the Ethereum mainnet.

4. **Scripting**: JavaScript scripts are written to automate tasks such as contract deployment, interacting with deployed contracts, or other operations related to the DApp.

5. **Integration and Frontend Development**: Once the smart contracts are deployed and tested, they can be integrated into a frontend interface using web development technologies such as HTML, CSS, and JavaScript. This frontend allows users to interact with the smart contracts through a user-friendly interface.

Overall, the project leverages a combination of Ethereum, Solidity, Hardhat, and testing frameworks to develop, test, and deploy decentralized applications with secure and reliable smart contracts.
