# CertiChain: A Blockchain-Based Digital Certificate Authentication System

## 📄 Overview

**CertiChain** is a decentralized application designed to authenticate academic certificates using blockchain technology. By leveraging the immutable nature of blockchain, CertiChain ensures that issued certificates are tamper-proof and easily verifiable by employers, institutions, and other stakeholders.

## 🚀 Features

- **Immutable Records**: Once a certificate is issued, its record on the blockchain cannot be altered or deleted.
- **Easy Verification**: Employers and institutions can verify the authenticity of certificates without intermediaries.
- **Decentralized Storage**: Eliminates the need for centralized databases, reducing the risk of data breaches.
- **User-Friendly Interface**: Intuitive UI for institutions to issue certificates and for verifiers to authenticate them.

## 🛠️ Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Blockchain**: Ethereum, Solidity
- **Smart Contracts**: Deployed using Truffle Suite
- **Storage**: IPFS (InterPlanetary File System) for storing certificate files
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: MongoDB

## 📂 Project Structure
```
CertiChain-A-Blockchain-Based-Digital-Certificate-Authentication-System/
├── client             / # Frontend React application
├── api                / # Backend Express server
├── contracts          / # Solidity smart contracts
├── migrations         / # Truffle migration scripts
├── test               / # Smart contract tests
├── uploads            / # Uploaded certificate files
├── .gitignore
├── README.md
├── package.json
└── truffle-config.js
```
# ⚙️ Setup Instructions

### Prerequisites

- Node.js and npm installed
- Truffle Suite installed globally
- Ganache CLI or Ganache GUI for local blockchain
- MongoDB installed and running

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Himanizambare/CertiChain-A-Blockchain-Based-Digital-Certificate-Authentication-System.git
   cd CertiChain-A-Blockchain-Based-Digital-Certificate-Authentication-System
   ```

### Install dependencies:

```
npm install
cd client
npm install
cd ..
```

### Compile and migrate smart contracts:

```
truffle compile
truffle migrate
```


### Start the backend server:
```
npm run server
```

### Start the frontend application:

```
cd client
npm start
```

### Access the application:

Open your browser and navigate to [http://localhost:3000](http://localhost:3000).


### 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.


   
