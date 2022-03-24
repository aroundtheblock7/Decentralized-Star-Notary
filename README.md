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
```cd app```
```npm run dev```

## Rinkeby deployment log
```
Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 29999915


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x0a6ad9a33012217268c646847142c1ee05870bbe1c684bbed9d9d6dfe58d95b1
   > Blocks: 1            Seconds: 4
   > contract address:    0x06EDD192db90aFfEf2e7869717395D9a690e9f0a
   > account:             0xFF985509Aa523FE9cd3d0A6891fCB9f2A4134feE
   > balance:             0.39520212
   > gas used:            239894
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00479788 ETH

   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00479788 ETH


2_deploy_contracts.js
=====================

   Deploying 'StarNotary'
   ----------------------
   > transaction hash:    0x082580ad77c6be8333e5a85e00b0a647cf04194f3c0f7cd1177ccdb5fc38c536
   > Blocks: 0            Seconds: 12
   > contract address:    0xa643b359fd3EFF4B69fa46e0b98774403fD48A1C
   > account:             0xFF985509Aa523FE9cd3d0A6891fCB9f2A4134feE
   > balance:             0.35058886
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
`0xa643b359fd3EFF4B69fa46e0b98774403fD48A1C`
