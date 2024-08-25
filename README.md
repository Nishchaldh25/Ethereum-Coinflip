# Ethereum-Coinflip
A blockchain-based Coinflip game built on the Ethereum testnet. Users can connect their wallet, place bets with test tokens (ETH), and flip a coin. The smart contract determines the outcome, doubling the bet if the user wins. Fully decentralized and hosted on Vercel with MetaMask wallet integration.

![screenshot](https://github.com/user-attachments/assets/c163493d-a4e7-4d98-9fb8-7e7a6d75ff71)

# Blockchain  Ethereum Coin Flip game :
This decentralized application is a blockchain-based coin flip game, allowing users to bet with ETH. The application integrates a smart contract developed in Solidity (CoinFlip.sol), with a sleek front-end built using Bootstrap 4 and Web3.js for Ethereum interactions.

Demo
http://coinflip.quequiereshacer.es/

# Game Overview
The game is simple and exciting. Players place their bets in ETH, and a virtual coin flip determines the outcome. If the coin lands on heads, the player wins 190% of their bet. If it lands on tails, the player loses their stake.

# Getting Started :
To start playing, users need to install the MetaMask browser extension. The game operates on the Rinkeby Ethereum test network, so ensure your MetaMask is connected to Rinkeby before engaging in the game.

# Don’t Have ETH to Play?
As this game operates on the Ethereum Rinkeby testnet, players can obtain free test ETH by setting up a Rinkeby account on MetaMask. Simply visit faucet.rinkeby.io and follow the instructions to get test ETH and begin playing without spending real funds.

# Technical Details :
The coin flip is determined based on the current block's timestamp. If the timestamp is odd, the result is heads, and the player wins 190% of their bet. If the timestamp is even, the result is tails, and the player loses the bet.

# Installation Instructions :
To set up your own version of the Coin Flip game:

1. Deploy the Solidity smart contract using your preferred Ethereum tool (e.g., Ethereum Wallet or Mist), and note the contract address. Make sure to fund the contract with enough ETH so it can payout winnings.

2. Edit the coinflip.js file and update it with your contract’s address.

3. Host the application on any static web server, or run it locally during development.

4. Enjoy the game!

# Roadmap :
# User Interface Improvements:
1. Implement DataTables (https://datatables.net) in Last Played Games.
2. Implement tabs, rename 'Last Played Games' to 'Last 10 Bets' and implement 'Wins' table.
3. Rewrite UpdateGamesTable() function to manage all table updates.
4. Change loading spinner, provide better gaming experience.
5. New website sections.
6. Try to explain the game better in jumbotron.

# Smart Contract Enhancements:
Set a maximum bet limit, ensuring any excess is returned to the player.
