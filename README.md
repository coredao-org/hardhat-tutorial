# Hardhat Tutorial

This project demonstrates how to compile, deploy and call smart contracts on Core TestNet using HardHat.

To run the project, you need to create a `secret.json` under the root folder and fill in as below. Or you can modify `hardhat.config.js` to setup your own configurations.

```json
{"PrivateKey":"you private key, do not leak this file, do keep it absolutely safe"}
```

Steps to run:

```shell
npm install
npx hardhat compile
npx hardhat test
npx hardhat run scripts/deploy-and-call.js
```

