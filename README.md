# Star Notary Blockchain app

Truffle version: v5.0.2

OpenZeppelin: 2.1.2
## How to use the project?

```npm install``` will install all the dependencies

In a seperate terminal connect via ganache to port 8545 with the commmand:
```ganache-cli```

In previous terminal (in root folder of project) run:
```truffle compile```

For migrating the contract to the locally running Ethereum network, inside the development console, run:
```migrate --reset```

For running unit tests the contract, inside the development console, run:
```truffle test```

For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run:
```npm run dev```

## Rinkeby deployment log
```
Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 30000000


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x52684026464a3df8c5342400d456a9f6f18b5b3931d82a22af2ca4f5a814972c
   > Blocks: 0            Seconds: 8
   > contract address:    0x32CcA129a8a3C9Fa512DE91e74D67e5e60cE481d
   > account:             0xFF985509Aa523FE9cd3d0A6891fCB9f2A4134feE
   > balance:             0.34579098
   > gas used:            239894
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00479788 ETH

   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00479788 ETH


2_deploy_contracts.js
=====================

   Replacing 'StarNotary'
   ----------------------
   > transaction hash:    0x15d492e0df427ac922d2821aa28a13d4a8bc40e43111dd8774f0929291181f0c
   > Blocks: 1            Seconds: 12
   > contract address:    0x80a5854Ec2575bcA486C1C2A30A66e0D3d7Ce2C3
   > account:             0xFF985509Aa523FE9cd3d0A6891fCB9f2A4134feE
   > balance:             0.30117772
   > gas used:            2230663
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.04461326 ETH

   > Saving artifacts
   -------------------------------------
   > Total cost:          0.04461326 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.04941114 ETH
```
## Rinkeby contract address
https://rinkeby.etherscan.io/tx/0x15d492e0df427ac922d2821aa28a13d4a8bc40e43111dd8774f0929291181f0c

Previous Rinkeby deployment from same account- 
https://rinkeby.etherscan.io/tx/0x082580ad77c6be8333e5a85e00b0a647cf04194f3c0f7cd1177ccdb5fc38c536

