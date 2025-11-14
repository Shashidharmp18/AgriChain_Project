🌾 Agricultural Supply Chain Management System
Blockchain-Based Traceability Using React, Solidity, Truffle & Ganache

This project provides a secure, transparent, and decentralized agricultural supply chain using Ethereum blockchain.
It tracks the complete journey of an agricultural product through four main actors:

Farmer

Manufacturer / Processor

Delivery Hub / Distributor

Customer

Each step is recorded immutably on the blockchain, and the frontend integrates with MetaMask for transactions.

🚀 Features
🔹 Blockchain Traceability

Stores every supply chain event on Ethereum.

Ensures transparency & tamper-proof records.

🔹 Role-Based Workflow

Farmer: Adds product/crop details.

Manufacturer: Updates processing information.

Delivery Hub: Adds shipping details.

Customer: Verifies product authenticity.

🔹 Smart Contract Powered

Written in Solidity

Managed using Truffle

Local blockchain via Ganache

🔹 React Frontend

Built using React + Vite

Uses Material UI / Tailwind CSS

Integrated with MetaMask

Real-time blockchain updates

🛠️ Tech Stack
Frontend

React (Vite)

Material UI or Tailwind CSS

JavaScript (ES6+)

Web3.js / Ethers.js

MetaMask Integration

Blockchain & Backend

Solidity

Truffle

Ganache

📁 Project Structure
eth-supplychain-dapp-main/
│
├── contracts/            # Solidity smart contracts
├── migrations/           # Truffle migration scripts
├── client/               # React frontend (Vite)
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── assets/
│
├── test/                 # Smart contract test cases
├── truffle-config.js     # Truffle config file
└── README.md

📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/agri-supplychain-blockchain.git
cd agri-supplychain-blockchain

2️⃣ Install Truffle
npm install -g truffle

3️⃣ Start Ganache

Open Ganache UI or use CLI:

ganache-cli

4️⃣ Compile & Deploy Contracts
truffle compile
truffle migrate --reset

5️⃣ Run Frontend
cd client
npm install
npm run dev

🔗 MetaMask Setup

Install MetaMask browser extension.

Import an account from Ganache using its private key.

Set network to: Localhost 7545.

Open the frontend → MetaMask will request connection.

🧪 Running Tests
truffle test

📸 UI Screenshots (Optional)

Add screenshots in this folder:

client/src/assets/screenshots/
farmer_dashboard.png
manufacturer.png
shipping_status.png
customer_verification.png

📘 How the System Works
1. Farmer

Registers product

Adds crop details

Sends product to manufacturer

2. Manufacturer

Receives raw materials

Updates processing details

Sends product to delivery hub

3. Delivery Hub

Updates shipping information

Transfers to customer

4. Customer

Scans/enters product ID

Verifies full history on blockchain

📜 Smart Contract Details
SupplyChain.sol

Includes functions to:

Register product

Update processing details

Update shipping

Confirm delivery

Retrieve full lifecycle data

🛡️ Security Highlights

Immutable blockchain records

Verified role-based transactions

Transparent product lifecycle

No central authority required

🚀 Future Enhancements

IPFS image/document storage

QR code verification

Mobile app version (Flutter)

Multi-chain deployment (Polygon, BSC, etc.)

AI-based quality prediction

👨‍💻 Contributors

Shashidhar M Patgar
Manjunath R
Shravan Poojary

📄 License

MIT License © 2025
