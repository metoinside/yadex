# Yet Another DEX

As it has many duplicates of the Uniswap DEX, YADEX is a copy of it while enabling the functionality in
- Linea Testnet: [0x06e40F49E71184d34eDDE4D14b55d37071A228d2](https://explorer.goerli.linea.build/address/0x06e40F49E71184d34eDDE4D14b55d37071A228d2)
- Polygon zkEVM Testnet: [0x63a4dab0be89f0153e73947d690d856e1a374ca5](https://testnet-zkevm.polygonscan.com/address/0x63a4dab0be89f0153e73947d690d856e1a374ca5)
- Mantle Testnet: [0x06e40F49E71184d34eDDE4D14b55d37071A228d2](https://explorer.testnet.mantle.xyz/address/0x06e40F49E71184d34eDDE4D14b55d37071A228d2)
- Arbitrium Sepolia: [0x06e40F49E71184d34eDDE4D14b55d37071A228d2](https://sepolia.arbiscan.io/address/0x06e40F49E71184d34eDDE4D14b55d37071A228d2)
- Scroll Sepolia: [0x5FbDB2315678afecb367f032d93F642f64180aa3](https://sepolia.scrollscan.dev/address/0x5fbdb2315678afecb367f032d93f642f64180aa3)

It was forked from the open source library of Scaffold-ETH-2 


Download & install dependencies by running:

```sh
git clone https://github.com/metoinside/yadex
yarn install
```

> in the same terminal, start your local network (a blockchain emulator in your computer):

```sh
yarn chain
```

> in a second terminal window, 🛰 deploy your contract (locally):

```sh
yarn deploy
```

> in a third terminal window, start your 📱 frontend:

```sh
yarn start
```

📱 Open http://localhost:3000 to see the app.

> 👩‍💻 Rerun `yarn deploy` whenever you want to deploy new contracts to the frontend. If you haven't made any contract changes, you can run `yarn deploy --reset` for a completely fresh deploy.
