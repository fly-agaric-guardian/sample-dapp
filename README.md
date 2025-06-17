# sample-dapp

//Test
npx hardhat test

//Compile after a change
npx hardhat compile

//Start node
npx hardhat node

//Make sure that ./ignition/parameters.json has the correct params

//Deploy
npx hardhat ignition deploy ./ignition/modules/Lock.ts --network localhost --parameters ./ignition/parameters.json

//Copy ./artifacts/contracts/Lock.sol/Lock.json abi list to client/src/utils/Lock_ABI.json

//Copy deployed address to client/src/utils/constants.js