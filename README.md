

# SolanaWatcher

**SolanaWatcher** is a simple tool for monitoring Solana wallet activity. It allows you to track transactions and changes for any Solana address, making it useful for portfolio tracking, real-time notifications, and wallet management.

---

## Features

- 🔔 **Watch Solana wallet addresses for activity**
- 📦 **Track incoming and outgoing transactions**
- 📊 **Monitor balance changes in real time**
- 🛠️ **Easy to configure and run**

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or newer)
- A Solana RPC endpoint (public or private)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/cccc9997/SolanaWatcher.git
   cd SolanaWatcher
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   - Copy `.env.example` to `.env` and fill in your configuration (such as Solana RPC endpoint and wallet addresses to watch).

   ```bash
   cp .env.example .env
   ```

   - Edit `.env` as needed.

### Usage

Start the watcher with:

```bash
node index.js
```

The script will begin monitoring the specified Solana wallet addresses and log activity to the console.

---

## Configuration

Edit the `.env` file to set:
- **RPC Endpoint:** Your Solana RPC URL
- **Wallet addresses:** List of Solana addresses you want to watch

Example `.env`:
```
SOLANA_RPC_URL=https://api.mainnet-beta.solana.com
WALLET_ADDRESSES=YourWalletAddress1,YourWalletAddress2
```

---

## License

MIT License

---
