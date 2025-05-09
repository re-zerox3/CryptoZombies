# The Phantom of Web3 zombie

Learning basic Solidity and Web3.js for bug bounty hunting through writing and interacting with smart contracts.
Smart contracts implements access-control functionalities and ownership when creating and interacting with tokenizable zombies.
Web3 is our front-end that interacts with our smart contract. It renders owned zombies and notifies user of any events. 
Web3 allows as smooth interaction with smart contracts on the Ethereum BlockChain through different services and extensions.

The spooky spells allow to summon zombies and multiply them by feeding them some delicious pure souls known cryptoCats.
CryptoKats are the main source of zombie growth. They are found on a realm called blockchain. 
We can only retrieve some data for artificial production to feed zombies.
![Cryptozombies](https://github.com/user-attachments/assets/94ccbb43-eff5-4219-9a6e-e8ed0e6c146e)

## ownable.sol
- Defines authorization control:
  - Defining and modifying contract ownership.
  - Access control to zombie ownership and the data factory.
## zombieFactory.sol
- Inherits access control functionalities from the Ownable contract.
- Defines the structure and characteristics of our zombies.
- Common functionalities for creating a zombie.

## zombieFeeding.sol
- imports Interface from public smart contract.
- Inherits from the ZombieFactory contract.
- Functionalities for creating special zombies
- Function to level up zombies and Fee.

## zombieHelper.sol
- Inherits from ZombieFeeding contract
- Helpers to facilitate some functionalities.

##zombieattack.sol
- Inherits from ZombieHelper contract
- Functions to determine the outcome of the attack via randomization. 

## zombieownership.sol
- Inherits from ZombieAttac and ERC721 contracts.
-  Ownership checks and functionalities
- Approval and transferring of Tradeable Zombie Tokens.

## safemath.sol
- Library for secure arithmetic.
- Safety checks to prevent overflow or underflow arithmetic.

## erc721.sol
- Implements common functionalities for tradeable tokens.
- Events(Transfer,Approval) and functions()

## index.html
- Web3.js front-end that interacts with smart contract.
- Function that are subscribed to events.
- Handles ether to wei exchange
- Renders zombies of user owner.

https://share.cryptozombies.io/en/lesson/6/share/The_Phantom_of_Web3?id=Y3p8NjUwNDMx









