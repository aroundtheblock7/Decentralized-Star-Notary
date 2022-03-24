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
		Using network 'rinkeby'.

		Running migration: 1_initial_migration.js
		  Deploying Migrations...
		  ... 0x21ff62ca26816c5983b9ce5a5e097a65b0c7eabccd014698551723226d26ef34
		  Migrations: 0xcc3b5cfffae19d5b7ec7639226a42f9193126557
		Saving successful migration to network...
		  ... 0xcc4c75cdc841fbe7422f070d3f15773552aefd1546d66b915e5b3fb49a206d67
		Saving artifacts...
		Running migration: 2_deploy_star_notary.js
		  Deploying StarNotary...
		  ... 0xafeef80a8dc1a4e27d5c06a85af9370f5d0c38dd1d048047cbc6f8a1c2106dc2
		  StarNotary: 0xfa096ec1127e1d195c3ae27e3a76b64117548a38
		Saving successful migration to network...
		  ... 0x543f00f90023f4e2b0f43d817c51da1dbc6fdcaf22760582c2cd2fbeea380038
		Saving artifacts...
```
## Rinkeby contract address
`0xfa096ec1127e1d195c3ae27e3a76b64117548a38`