# UAP DAO
This serves as a temporary public repo for the UAP DAO,  a decentralized autonomous organization aiming to accelerate R&D and awareness of UAPs and related phenomena.

Within this repo is a cloned 'scaffold-eth' dir that contains an example ETH dapp.
***scaffold-eth requires the lts version of node***
- To start 👷‍ Hardhat chain:
```
cd scaffold-eth
yarn install
yarn chain
```

- in a second terminal window, start 📱 frontend:
```
cd uap-dao/scaffold-eth
yarn start
```

-in a third terminal window 🛰 deploy your contract:
```
cd uap-dao/scaffold-eth
yarn deploy
```

🔏 Edit your smart contract YourContract.sol in packages/hardhat/contracts

📝 Edit your frontend App.jsx in packages/react-app/src

💼 Edit your deployment scripts in packages/hardhat/deploy

📱 Open http://localhost:3000 to see the app
