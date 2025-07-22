# Plume Swap Bot ( Plume Guardian )

A lightweight Node.js bot to automatically swap between **PLUME** and **pUSD** on the Plume chain. Great for automation or airdrop farming.

![sda](https://github.com/user-attachments/assets/1a024800-d218-40dd-a189-38781266ab78)

---

## 📦 Installation

Clone the project and install dependencies:

```bash
git clone https://github.com/tihorsliced/auto-swap-plume-mainnet.git
```
```bash
cd auto-swap-plume-mainnet
```
```bash
npm install
```

## ⚙️ Environment Setup
Create a .env file in the root directory:

```bash
nano .env
```
Input your private key and wallet address
You can change the random config as you wish

```bash
PRIVATE_KEY=your_private_key
WALLET_ADDRESS=your_wallet_address
PLUME_RPC=https://phoenix-rpc.plumenetwork.xyz

MIN_PLUME=5
MAX_PLUME=15
MIN_PUSD=0.5
MAX_PUSD=1.5

MIN_TX=10
MAX_TX=30
MIN_DELAY=60
MAX_DELAY=180
```

## ▶️ Run the Bot
To run the automated PLUME ↔ pUSD swap bot:

```bash
node index.js
```
It will perform a random number of swap transactions with randomized amounts and time delays.

##
#plume #airdrop #swap #bot #crypto #web3 #automation #trading #pUSD
