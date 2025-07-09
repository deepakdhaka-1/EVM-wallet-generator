# 🔥 EVM Wallet Generator CLI

A lightweight and powerful command-line tool to generate one or many **Ethereum Virtual Machine (EVM)** compatible wallets. Ideal for airdrop hunters, smart contract testers, or anyone managing large-scale wallet setups.

---

## ⚙️ Features

- 🔐 Generates secure 12 or 24-word **BIP39 mnemonic phrases**
- 🧠 HD wallet derivation using `m/44'/60'/0'/0/i` (standard for Ethereum and EVM chains)
- 💼 Outputs wallet details including:
  - Mnemonic
  - Private Key
  - Public Key
  - EVM Address (0x...)
- 🌀 Supports bulk generation — create hundreds or thousands of wallets in one go
- 💾 Saves results to a neatly formatted `evm_wallets.csv` file
- ⚡ Fast and efficient — generates 100 wallets in seconds
- 🧰 Easily extendable for:
  - CSV exports
  - Wallet funding
  - Batch transaction tools
  - QR code generation

---

## 📦 Installation

```bash
git clone [https://github.com/deepakdhaka-1/EVM-wallet-generator
cd evm-wallet-generator-cli
pip install -r requirements.txt
```
## Main command
```bash
python3 main.py
# or
python main.py
```
# To Copy content of wallet `evm_wallets.csv` file.
```bash
cat evm_wallets.csv | clip.exe
```
-This command will copy the content of evm wallets on your clipboard, paste it in any excel or safe location.
