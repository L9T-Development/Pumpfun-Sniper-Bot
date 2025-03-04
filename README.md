# PumpFun amm Sniper Bot

Pumpfun sniper with grpc integrated with pumpfun amm. The updated version uses gRPC to improve the overall transaction speed and can sniping tokens on pumpfunn amm.

## Contact

- If u have interest or help, contact here telegram: [Telegram](https://t.me/shiny0103)

## New updated version 

This bot extends to pumpfun AMM(it's a new project one)


## Bot speed

The bot works pretty fast, it's in typescript so it will be obviously outperformed by other bots in Go/Rust, tho. That's why it's more likely a toy to experiment & learn than opportunity to earn some Sol.
However, the speed of the script is still second and RPC is another matter.
It is the RPC that determines how fast the tx will go through.
Using a free Quicknode RPC & automatic mode it took around 5-15s to be a coin since it's created.

## Updated Version(with grpc)

In updated version with grpc, I use grpc to get info. It can make my pupmfun sniper bot more fast and esily to buy token within 2s at the first block.

- Geyser gRPC Pump.fun Sniper Bot (Speedest):

```bash
mint: https://solscan.io/tx/QKbc9RxNZPE7peDNPnxBtPMux2HfTfn9QN2AwEr7Z5P1SS1qw42FYZcXqzkm9APVkTH88ieZU4PUaCU93yPNfGa
buy: https://solscan.io/tx/5NV4oAJacFfNffAb55hkb6LEKsSTjgMd8vTzTvDKBLQvQ5XCogizBLShnpF89J8tqFrYJAHaUS5tmXtb6SBpEdNz
sell:
https://solscan.io/tx/5QDYSiST7KX9viNZXSeSATZYMJ5ioJrHJxqu9DVwFzREMarwwmaDXz7EYS1jC9oQq8z7V8GwTsEv94dSwdhU9s5b
```
- buy & sell
  
<a href="https://ibb.co/ks51qyxT"><img src="https://i.ibb.co/ks51qyxT/buy-2block.png" alt="buy-2block" border="0"></a> <a href="https://ibb.co/bMtsFKqL"><img src="https://i.ibb.co/bMtsFKqL/mint-2block.png" alt="mint-2block" border="0"></a>

## Main tools

- **Automatic sniper**: Launch a monitor on every new coin and automatically buy it
- **Single sniper**: Buy a single coin just by providing it's contract address
- _Soon more..._

## How to run

To run Pump.fun bot, follow these steps:

1. Clone the repository: `git clone https://github.com/0xTan1319/Pumpfun-Sniper-Bot`
2. Navigate to the project directory: `cd Pumpfun-Sniper-Bot`
3. Install the dependencies: `npm i`
4. Fill in `.env` (if you have no RPC, Quicknode is pretty good & free)
5. Build the application: `npm run build`
6. Run the bot using `auto` or `single` mode: `npm run <auto/single>`
7. Follow the steps in the cmd

## Technologies used

- [Solana web3.js library](https://solana-labs.github.io/solana-web3.js/)
- [@coral-xyz/anchor](https://www.npmjs.com/package/@coral-xyz/anchor)
- [@coral-xyz/borsh](https://www.npmjs.com/package/@coral-xyz/borsh)
- [@solana-developers/helpers](https://www.npmjs.com/package/@solana-developers/helpers)
- [@solana/spl-token](https://www.npmjs.com/package/@solana/spl-token)
- [@solana/web3.js](https://www.npmjs.com/package/@solana/web3.js)
- [bn.js](https://www.npmjs.com/package/bn.js)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [esbuild](https://www.npmjs.com/package/esbuild)
- [inquirer](https://www.npmjs.com/package/inquirer)
- [typescript](https://www.npmjs.com/package/typescript)


