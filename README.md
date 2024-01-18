# CSCI 4312: Voting DAPP using smart contracts

GROUP 5

- Member Name:
  - MUHAMMAD HANIFF BIN ISMAIL(2110619)
  - MUHAMMAD SYAZWAN BIN MAT SHUKI(2119861)
  - HARIZ SYAHMI BIN HAIRO ROSE SIDI(2115575)

## Dependencies

Install these prerequisites to follow along with the tutorial.

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Step 1. Install dependencies

```
$ cd voting-dapp
$ npm install
```

## Step 2. Start Ganache

Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

## Step 4. Compile & Deploy Election Smart Contract

`$ truffle compile`
`$ truffle development`
`$ migrate --reset`
`$ .exit`
`$ truffle deploy`

You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask

Follow below steps after metamask extention is downloaded

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache (port number is 7545 and chain ID is 1337).
- Import an account provided by ganache.

## Step 6. Run the Front End Application

`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

