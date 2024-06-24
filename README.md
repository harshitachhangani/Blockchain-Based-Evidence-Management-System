# Forensic Evidence Management System

This project is a Forensic Evidence Management System leveraging blockchain technology to enhance the integrity, security, and transparency of evidence handling processes. It utilizes Ethereum smart contracts and integrates with IPFS for decentralized storage.

## Overview

The Evidence Management System (EMS) employs blockchain technology to fortify security and transparency in evidence handling. Smart contracts autonomously manage tasks such as evidence submission, retrieval, and access control, fostering a culture of transparency and accountability. Integration with Metamask democratizes user interaction with Ethereum smart contracts, making evidence management intuitive and inclusive.

## Features

- **Decentralized Storage**: Uses IPFS for tamper-proof, distributed storage of evidence files.
- **Smart Contracts**: Manages evidence lifecycle (submission, retrieval, access control) autonomously on the Ethereum blockchain.
- **User Interaction**: Metamask integration for secure and user-friendly interaction with the blockchain.
- **Transparency and Security**: Immutable records of evidence handling ensure transparency and prevent tampering.

## Components

### Frontend Integration

The frontend integrates with Metamask for user authentication and interaction with the smart contracts. Users can submit new evidence, retrieve existing evidence details, and view the total number of evidence records.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Truffle](https://www.trufflesuite.com/truffle)
- [Ganache](https://www.trufflesuite.com/ganache)
- [Metamask](https://metamask.io/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/forensic-evidence-management.git
   cd forensic-evidence-management


2. **Install dependencies**
   ```bash
   npm install
4. **Compile the smart contracts**
   ```bash
   truffle compile
6. **Migrate the smart contracts**
   ```bash
   truffle migrate

### Running the Application

1. **Start the local blockchain**
   ```bash
   ganache-cli
2. **Run the frontend application**
   ```bash
   npm start
4. **Interact with the application**
   - Open your browser and navigate to http://localhost:3000
   - Connect your Metamask wallet
   - Use the interface to add and view evidence reports

### Usage
- Adding a Report
- Connect your Metamask wallet.
- Fill in the form with crime details and upload the evidence file to IPFS.
- Submit the form to record the evidence on the blockchain.
- Viewing Reports
- Navigate to the reports section.
- Enter the index of the evidence to view its details.

