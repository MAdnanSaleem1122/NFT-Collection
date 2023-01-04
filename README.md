# NFT-Collection

![nft2](https://user-images.githubusercontent.com/121422342/210506653-1d9fb752-6f5c-4653-994e-7d3dcbd7b71e.PNG)

To setup a Hardhat project, Open up a terminal and execute these commands
```
mkdir NFT-Collection
cd NFT-Collection
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
```
In the same directory where you installed Hardhat run:
```
npx hardhat
```
Make sure you select Create a Javascript Project and then follow the steps in the terminal to complete your Hardhat setup.
In the same terminal now install @openzeppelin/contracts as we would be importing Openzeppelin's ERC721Enumerable Contract in our CryptoDevs contract.
```
npm install @openzeppelin/contracts
```
Create a new file inside the contracts directory and call it IWhitelist.sol

Now let's create a new file inside the contracts directory and call it CryptoDevs.sol
Now let's install dotenv package to be able to import the env file and use it in our config. Open up a terminal pointing at hardhat-tutorial directory and execute this command.
```
npm install dotenv
```
Compile the contract, open up a terminal pointing at hardhat-tutorial directory and execute this command
```
npx hardhat compile
```
To deploy, open up a terminal pointing at hardhat-tutorial directory and execute this command
```
npx hardhat run scripts/deploy.js --network goerli
```
You would need to create a new next app. Your folder structure should look something like
```
- NFT-Collection
       - hardhat-tutorial
       - my-app
       ```
To create this my-app, in the terminal point to NFT-Collection folder and type
```
npx create-next-app@latest
```
Now to run the app, execute these commands in the terminal
```
cd my-app
npm run dev
```
Open up a terminal pointing atmy-app directory and execute this command
```
npm install web3modal
```
In the same terminal also install ethers.js
```
npm install ethers
```
