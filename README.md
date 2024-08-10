# bsc-wallet-generator
A simple Node.js function to generate Binance Smart Chain (BEP20) wallets using BIP39 and ethers.js. This utility generates a mnemonic, derives the private key, and outputs the BNB address and related details.

## Repository Structure:
```
/bsc-wallet-generator
│
├── /src
│   └── generateWallet.js
│
├── .gitignore
├── README.md
├── package.json
└── LICENSE
```
## Installation:
```bash
git clone https://github.com/hashHubTech/bsc-wallet-generator.git
cd binance-wallet-generator
npm install
```
## Usage:
```javascript
import { generateBinanceWallet } from './src/generateWallet';

generateBinanceWallet().then(wallet => {
  console.log(wallet);
});
```
## Output:
```json
{
  "ticker": "BNB",
  "address": "0x...",
  "privateKey": "0x...",
  "mnemonic": "..."
}
```
## Licence:
This project is licenced under the MIT Licence
