# Forking the Ethereum Mainnet with Hardhat

Fork the Ethereum Mainnet to see its state at any given point

## Getting Started

First, install dependencies:

```
pnpm install
```


### Run the forked mainnet

You can run the fork by running:

```
pnpm fork
```

To run the fork at a specific block, use `fork-block` instead and pass it the block number as an argument:

```
pnpm fork-block 12799760
```

This will let you to query for that specific block:

```
pnpm query-block
```
