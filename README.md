# Insurance Transfer DApp - Scroll City Cup Hackathon

![logo](https://github.com/user-attachments/assets/7e23684c-31f9-4b25-8424-4ecde756f338)

Author: Konstantinos Andreou


## Description

The Insurance Transfer DApp facilitates secure and authenticated transfers of Ether between parties. It integrates additional authentication measures to prevent the loss of funds due to mistyped wallet addresses.

## Features

- Secure transfer of Ether with claim and claimBack functionalities.
- Handles multiple transactions simultaneously.
- Stores transaction details securely to ensure transparency and verifiability.


## Smart Contract Deployment

- The smart contract is deployed on the Scroll Sepolia Testnet network.
- Contract address: [0x3fba18D8F201B57F72A979bE5CBe17E81CE08F01](https://sepolia.scrollscan.com/address/0x3fba18D8F201B57F72A979bE5CBe17E81CE08F01#code)


## Live Demo

- Test the application at: [Live Demo](https://insurancetransferscroll.netlify.app/)

## Technologies and Tools Used

- **Remix IDE:** Used for developing and deploying the smart contract.
- **OpenZeppelin:** Utilized for securing the smart contract with standard libraries.
- **React:** A JavaScript library for building user interfaces.
- **JavaScript:** The primary programming language for front-end development.
- **thirdweb SDK:** Simplifies wallet connection and contract interaction.
- **ethers.js:** A library for interacting with the Ethereum blockchain.
- **walletconnect:** Enables connecting mobile wallets to the DApp.
- **Next.js:** A React framework for server-side rendering and generating static websites.

## How to Use

1. **Send Ether**: Use the form to send Ether to another address.
2. **Claim Ether**: The designated receiver can claim the Ether by providing the sender's address.
3. **Claim Back Ether**: The sender can reclaim the Ether if it hasn't been claimed by the receiver.


## Security Measures

- Utilizes OpenZeppelin's ReentrancyGuard to protect against reentrancy attacks.
- Implements comprehensive modifiers to ensure that only the designated sender or receiver can claim or reclaim the transfers.
- Ensures that each transfer must be claimed or reclaimed before a new transfer can be initiated by the same sender.


## Contact

- **Author**: Konstantinos Andreou
- **LinkedIn**: [andreou00](https://www.linkedin.com/in/andreou00/)
- **Telegram**: [andreou00](https://t.me/andreou00)

For any inquiries or support, please contact me through LinkedIn or Telegram.
