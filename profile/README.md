# :moon: Moonkey wallet

**MoonKey** is a self-custodial smart wallet, powered by an Account Abstraction with ERC4337 standard.

**MoonKey** features a P2P fiat on-ramp, with anonymous crypto buy and sell, a built in editor and solidity compiler.

Unlike many other wallets that prioritize DeFi functionality, MoonKey has been designed with gamers as a priority. The user interface is simple, intuitive, and easy to navigate, making it a great choice for anyone looking to get started in the world of crypto gaming.

## Features

### P2P fiat on-ramp:

The P2P fiat on-ramp is for users to buy and sell cryptocurrencies without having to go through a centralized exchange.
This is achieved through the use of a mixer-like pool for order books and a decentralized conflict resolution mechanism and decentralized encrypted fiat address storage on IPFS.

1. _Anonymous transactions_: P2P transactions are entirely anonymous because neither the buyer nor the seller will be able to link the wallet associated with the counterparty's fiat account owing to the mixer-like pool for order books.
2. _Decentralized conflict resolution_: decentralized conflict resolution is ensured by the staking mechanism utilized for third-party voting. Moderators are encouraged to vote for the true appeal and are subject to slashing if their vote is malicious.
3. _Decentralized fiat address storage_: Data required for the P2P on/off-ramp, such as a fiat bank account or email address containing private or identifying information, is stored in a secure location that is only accessible to the counterparty making the deposit (the buyer).

### Mods

Anyone can design a mod and provide it in Moonkey, which allows users to find and administer it. Mods include Paymaster, Session-key, Transaction Guard, and ERC20 Paymaster. Mods are similar to the look of app stores, this will unlock the potential of smart-wallets.

Alternatively users can program and deploy contracts from within the wallet. With this feature it is possible to edit the wallet it-self, thus the next step of self-custody is programmbality and openness to modification, which are the designs of moonkey wallet.

### Moons

Moons are third-party dapps within Moonkey. Any dapp supporting either the ERC-4337 wallet or wallet-connect, from web3 games to swapping pools or DAOs, can be a moon (a widget inside MoonKey wallet that let's users interact with the dapp logic).

## Guide

Visit [web source code](https://github.com/moonkey-global/moonkey-bnb) for frontend.

Visit [contract source code](https://github.com/moonkey-global/moonkey-contracts) for ERC-4337 safe contracts.

Visit [on-ramp source code](https://github.com/moonkey-global/on_ramp) for ZK circuits and contracts of P2P on-ramp.

## Gallery

Home page
![Home screen](moonkey.png)

Assets page
![Assets screen](moonkey-assets_.png)

Mod page
![Mods screen](moonkey-mods_.png)

Moons page (Dapp lists)
![Moons screen](moonkey-moons_.png)
