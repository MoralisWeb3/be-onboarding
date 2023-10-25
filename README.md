# be-onboarding

## HOMEWORK 1 - Simple NFT API

The task is to develop a simple NFT API that returns all NFTs owned by an address on the Optimism network.

For example if the user inputs `0x35daf2acb874b377ff49cc2aac45dff3a0a9f753` we want to return the following output:

```
[
  {name:"Optimistic Goosey (Goseman)", amount: 1},
  {name:"Optimistic Plebe Pill", amount: 1}
]
```

You can see which NFTs the user has on Optimism by going to [this website](https://zora.co/0x35daf2acb874b377ff49cc2aac45dff3a0a9f753?enjoy=collected) in order to verify the solution.


### Limitations of the Scope

Below are some important limitations of the scope of this assignment that will make it way easier.

1. You know that the user only has NFTs that are compliant with the ERC1155 standard.
2. You know that the user received/minted all their NFTs between the 15th and 25th of October 2023.

### Tools allowed

1. Optimism RPC Node - you can use any provider you like
2. Database of your choosing if you need one
3. Programming language/framework of your choosing
4. Obviously using any third-party web3/blockhain/crypto APIs (except for an RPC node with standard RPC procedures) is not allowed


## HOMEWORK 2 - API for Own NFTs

1. Install Metamask, get some assets into your Metamask and buy some NFTs on OpenSea. Get some NFTs on Polygon, Optimism and Base networks.
2. Use your code from `HOMEWORK 1` to build an API where you can input your own address and get an array with all your NFTs across all chains. Example output below.

```
[
  {name:"Optimistic Goosey (Goseman)", amount: 1, chain: "Optimism"},
  {name:"Optimistic Plebe Pill", amount: 1, chain: "Polygon"}
]
```
