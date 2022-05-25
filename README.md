# PancakeSwap or other on bsc chain auto trade bot

![Auto](./screenshots/logo.jpg)


Inspired by the uniswap arbitrage bot blog

# features

- [x] Automatic monitoring of liquidity
- [x] Auto swap token choose a best route same like pancakeswap
- [x] Automatically sell when the token value doubles
- [x] Automatic stop loss when the price drops

# 📈 future
- [ ] I will productize it.
- [ ] Supports multiple wallets, multiple tokens, and automatic task management.
- [ ] Support UI manager.
- [ ] SUpport more public chain like heco bsc and more.

## ✨ screenshots
monitor wallet and liq
![Auto](./screenshots/img.png)

start trade
![Auto](./screenshots/img_1.png)

auto check sell point
![Auto](./screenshots/img_2.png)

## 💡 Installation.

Download & Install Node here :
https://nodejs.org/en/download/

Then run command prompt or powershell

- Type ``cd bsc-trade-bot-v1.0`` (replace with your cloned/downloaded bot folder)
- Type ``npm i``

## 🗺️ Usage  

1. Copy/rename **example.env** to **.env** ``cp example.env .env``
2. Provide your private key to .env PRIVATE_KEY field.
3. Install dependencies `npm i` or `yarn` if not already completed above.
4. Start the bot using `npm run start -- --with` or `yarn start -- --with`
5. Enjoy!

### 🦊 How to Export Private Key from MetaMask
1. Open your account
2. Click on three points at top-right corner
3. Account details
4. Export Private Key.

### ✔️ Sample ``.ENV`` file
```
ROUTE_SWAP_CHOOSE=pancakeswap
MAX_TAKE_PROFIT_POINT=1.5
MIN_STOP_LOSS_POINT=0.5
WALLET_PRIVATE_KEY=YOUR_PRIVATE_KEY_HERE
# token address which you want
SWAP_OUTPUT_TOKEN=0x6a79e08db6c08b8f88703794bf1a47f5a01eb9dc
```