# evoting-dapp
Blockchain based voting app

## Installation 
### Prerequisites 
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle

> `npm install -g truffle`
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Step 1. Clone the project
`git clone https://github.com/manisaiprasad/evoting-dapp`

## Step 2. Install dependencies
```
cd evoting-dapp
npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000
