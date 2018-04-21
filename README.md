# Welcome to Cryptoman!

Cryptoman was created in Unity3D and uses the Ethereum blockchain via Nethereum to submit / track scores. I have also gone about storing the game up on IPFS.  (I had a much more different direction at first for how to use the ethereum network, but due to issues and time constraints, I opted for the score submission)

### IPFS Address location is: https://gateway.ipfs.io/ipfs/QmUQyuwMw9CExrgfa4zbztW81YkyWhXan7NE5mDD7wsHQK/

This was created as a midterm project submission for Siraj Raval's Decentralized Applications course: https://www.theschool.ai/courses/take/decentralized-applications


## Notes

* You must run Metamask and be on the Ropsten Test Network to submit your high scores
* Still learning this stuff, so not fully sure how long the above IPFS address will work
* You will find both a token and the playerScore solidity contracts in the solidity_contracts folder, however I was never able to get around to implementing the usage of my custom Token. 
	* The contract address for the deployed token is: 0x511839503f822889ca90f003ef5563d4c4876595
	*	The token name is: Crypto Man Token
	* The token symbol is: CMT

* I've submitted only the core contract files and implementation files as the full unity project in the end was far too big

## How to play

1. Use your keyboard arrow keys to move left and right
2. Jump using either the space bar or your primary mouse button
3. Try to navigate around the platforms and jump off the walls before the encroaching flames melt your metal
4. You have three lives and then the game is over
5. For you to submit your score, it will require some coin, so make sure you use the faucet to populate some coin in your wallet
6. Have fun!!

## Stack used to create the game
* Unity3D
* Ethereum
* Nethereum - Unity / ethereum communication
* Web3 for metamask handling
* http://remix.ethereum.org/ for contract deployment
* IPFS for data storage

## Special Thanks
I just wanted to send out a special thanks to **Juan Blanco** for patience and assistance with Nethereum and the countless issues I managed to get myself into through this process. I would also like to give a shout out to **Siraj Raval** for putting this course together.  The structure and fun topics have been making this blockchain venture much more enjoyable. 
