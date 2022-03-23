# Star Notary Blockchain app

Truffle version: v5.0.2

OpenZeppelin: 2.1.2

"Contract Address” on the Rinkeby Network: 0x1F6A4a4c011EC21C076F33799B32a0d97722ebE0

## How to use the project?

Must be connected via command line with ganache-cli on port 8545! 
Connect with command...
ganache-cli (This will connect you via port 8454)

For starting the development console, run:
truffle develop

For compiling the contract, inside the development console, run:
compile

For migrating the contract to the locally running Ethereum network, inside the development console, run:
migrate --reset

For running unit tests the contract, inside the development console, run:
test

For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run:
cd app
npm run dev

When connecting Via Metamask make sure you are on localhost 8545 (not 9545) and your account is funded with test ETH.
In metamaks you can import accounts (using private key) from truffle develop console into metamask to fund account with test ETH.