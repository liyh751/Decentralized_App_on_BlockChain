This project is a crypto game of patronus. The dapp uses Metamask as the gateway, React APP as the frontend, and is deployed with truffle and Ganache.

## Steps for Deployment

- Install Ganache and start a Ganache workspace by running **`ganache-cli -p 7545`** 
- Use Truffle to compile our project **`truffle compile`** . If you want to deploy it to other network, you can change the information about the network in file truffle-config.js.
- Run **`truffle migrate`** to deploy the peoject. Copy the contract address to the ContractAddress.json file and change the address of the project under your network ID. The networkID of Ganache is 5777.
- Make sure you have Metamask wallet installed before you start the project.
- In the project directory, run **`npm install`** to install necessary dependencies then run **`npm run start`** to start the project and you can view it in your browser. 

## User Guide
- After running the command to start Patronus, an opening cinematic of HP will invite you to the world of magic and mystery. 

![image](https://github.com/Yihan222/6883Patronus/blob/67af7cf44188abe8daa4aaf7f03a5e31bac3f097/gif/app.gif)


- Link your MetaMask to Patronus, Click My Patronus and adopt your first ramdon figure of patronus for free.(Although gas fee is still needed) After that, you can buy as many patronus as you want at this page, of which the figures are also randomly given.

![image](https://github.com/Yihan222/6883Patronus/blob/67af7cf44188abe8daa4aaf7f03a5e31bac3f097/gif/adopt.gif)


- Click the image of each patronus, you can see the detail information about it. Feed your patronus every day, and pay some crypto coins to upgrade them. Patronus with levels above 2 are able to change their names.

![image](https://github.com/Yihan222/6883Patronus/blob/821501a031db6095369254a4cc213e9ff2a1de72/gif/FeedAndRename.gif)


- If you have a duplicate patronus figure and want to sell it, just click the patronus image, set a price and click "Sell it". Then you can find its information posted in the Patronus Market. You can still feed it and upgrade it before the patronus is picked by other players.

![image](https://github.com/Yihan222/6883Patronus/blob/67af7cf44188abe8daa4aaf7f03a5e31bac3f097/gif/sell.gif)


- You can also buy a patronus in the Patronus Market. Here, you may find new patronus figures or patronus with high level.

![image](https://github.com/Yihan222/6883Patronus/blob/67af7cf44188abe8daa4aaf7f03a5e31bac3f097/gif/buy.gif)

- There are totally nine figures Patronus. Try to get a whole set of Patronus and let your journey begin!
