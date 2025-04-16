# 🪙 Decentralized PayPal (Ethereum)

A decentralized peer-to-peer payment application powered by Ethereum blockchain, Solidity smart contracts, React frontend, Tailwind CSS, and Ethers.js.

---

## 🚀 Project Overview

This decentralized PayPal-like application allows users to securely and transparently send and receive Ethereum through the Ethereum blockchain.

---

## 🛠️ Technology Stack

| Layer                 | Technology                      |
| --------------------- | ------------------------------- |
| **Frontend**          | React.js, Tailwind CSS          |
| **Smart Contract**    | Solidity (Ethereum Blockchain)  |
| **Web3 Integration**  | Ethers.js                       |
| **Wallet Management** | MetaMask                        |

---

## ⚙️ Smart Contract

### Contract Functionalities:
- Transfer Ethereum securely.
- Save transaction history.
- Add and manage recipients.

### Events:
- `transactions`: Logs every transfer made between users.
- `recipients`: Logs when a recipient is added.

---

## 📁 Project Structure

```
decentralized-paypal/
├── public/
└── src/
    ├── components/
    │   ├── GlobalTx.js
    │   ├── Header.js
    │   ├── Login.js
    │   ├── Main.js
    │   ├── RecentTx.js
    │   ├── Recipients.js
    │   └── Send.js
    ├── paypal/
    │   ├── paypal.json
    │   └── paypal.sol
    ├── App.js
    ├── index.css
    ├── index.js
    └── reportWebVitals.js
```

---

## ⚡ Quick Start

### Step 1: Clone repository
```bash
git clone <repository-url>
cd decentralized-paypal
```

### Step 2: Install dependencies
```bash
npm install
```

### Step 3: Compile & Deploy Smart Contract

- Use Remix IDE or Hardhat to compile and deploy `paypal.sol` to Ethereum Testnet.

### Step 4: Run React frontend
```bash
npm start
```

Open `http://localhost:3000` in your browser.

---

## 🔐 Wallet Connection

Connect your Ethereum wallet (e.g., MetaMask) for sending/receiving transactions.

---

## ✅ Deployed Contract Addresses

```plaintext
Polygon: 0x9Ad232e2D3812d5E915B864119f8212D51BFB9F5
Ropsten: 0xa02b2CCE714f874AD7593f50012c5d3756BF2773
Rinkeby: 0x6170b96101557cc11F076AA3907F7FF870b54EE7
```

---

## 🌟 Contributing

Feel free to contribute improvements or enhancements:
- Fork repository
- Create branch (`git checkout -b feature/new-feature`)
- Commit changes (`git commit -m 'Add new feature'`)
- Push (`git push origin feature/new-feature`)
- Open Pull Request

---

## 📜 License

MIT License
