# DAO-dApp

This project's origin is the LearnWeb3 Sophomore course. The title is "Build a DAO for your NFT holders"

This DAO project is a decentralized autonomous organization that allows __NFT holders of previous project__ to create and vote on proposals to use the ETH collected from an ICO to purchase other NFTs from a Fake NFT marketplace. The goal of the DAO is to speculate on the price of NFTs and split the profits among all members of the DAO when the NFTs are sold back.

## Features

- Participants can create proposals to purchase NFTs from an NFT marketplace
- Participants can vote for or against proposals
- Each NFT counts as one vote for each proposal
- Voters cannot vote multiple times on the same proposal with the same NFT
- If a majority of the voters vote for the proposal by the deadline, the NFT purchase is automatically executed
- DAO Treasury is used to purchase NFTs

## How to Use

To use the CryptoDevs DAO, you must first have a CryptoDevs NFT which you can see details here. Once you have a CryptoDevs NFT, you can:

- Connect your wallet to the DAO dApp
- Create a proposal to purchase an NFT from an NFT marketplace
- Vote for or against proposals
- Wait for the voting deadline to expire
- If the proposal receives a majority of the votes, the NFT purchase is automatically executed

## Run the development server:

Open terminal and go `/frontend` directory.

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


For more info: [LearnWeb3 Sophomore Track](https://github.com/LearnWeb3DAO/Sophomore-Track/blob/main/Decentralized-Autonomous-Organizations.md)


## License

This project has an MIT License.
