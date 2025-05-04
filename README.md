# CryptoZombies
Building a zombie factory and production while learning smart contract development.
In our spooky lab, we cast powerful spells to make contracts with the underworld to establish a smart connection.

These spooky spells allow us to summon zombies and multiply them by feeding them some delicious pure souls named cryptoCats.
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
- Inherits from the ZombieFactory contract.
- Functionalities for creating special zombies
## zombieHelper.sol
- Helpers to facilitate some functionalities.
