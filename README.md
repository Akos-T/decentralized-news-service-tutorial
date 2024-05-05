# Decentralized News Service Tutorial

Building a decentralized news service with Chainlink Functions and Hacker News API

(Block Magic Hackathon Session)

## Instructor

Richard Gottleber - @thergdev

## YouTube

https://www.youtube.com/watch?v=8iLuNx9jYSo

## Written Tutorial: "Blockchain Masterclass for JavaScript Developers"

https://cll-devrel.gitbook.io/javascript-for-blockchain-master-class/decentralized-news-service-contract

## JavaScript code in Functions Playground

https://functions.chain.link/playground/b44eba0d-4498-48c5-a675-81780fc6873e

## Smart Contract

### Solidity code

[functions.sol](/contracts/functions.sol)

### Contract Address

`0xb835b0F63F411482B4EA0cfbD47Fe6BD6949AD70`

### Chainlink Functions Subscription

`https://functions.chain.link/sepolia/2489`

## How to run the frontend?

0. **Prerequisite:** Have the smart contract deployed and run sendRequest a few times
1. Clone the repository
2. Run `npm install` within the `frontend` folder
3. Create a `.env` file in the project root folder with the following content:

```
# RPC for sepolia (Change this if you want to use a different chain)
PROVIDER_URL="https://rpc.sepolia.org"

# CHANGE THIS TO YOUR CONTRACT ADDRESS!
CONTRACT_ADDRESS="0xb835b0F63F411482B4EA0cfbD47Fe6BD6949AD70"
```

4. Run `npm run dev` in the terminal from the `frontend` folder
5. Open page at `http://localhost:4321` or with the given port if you changed it
