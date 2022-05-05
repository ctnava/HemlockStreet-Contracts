# HemlockStreet || Contracts

## Commands
deploys and records addresses
```
yarn deploy // deploys to localhost

yarn networks // shows available networks 
yarn deployTo <NETWORK> // deploys to "network"
```


'yarn test' runs the automated tests

'npx hardhat console --network localhost' puts you into the sim blockchain
```
// instantiates an interface
const contract = await ethers.getContractAt("DStor", "0x9fE46736679d2D9a65F0992F2272dE9f3c7fa6e0")
  

const name = await contract.name() //hit enter to make a getter
name // just type it in and it will print

.exit
```