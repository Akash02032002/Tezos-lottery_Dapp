# Tezos-lottery_Dapp

This is a lottery dapp written in smartpy.

This is a SmartPy contract that implements a lottery game. It has two entry points: buy_ticket and end_game.

The buy_ticket entry point is used by players to purchase lottery tickets. Before buying a ticket, the contract checks if there are still tickets available to purchase and if the player has sent enough amount of tez to purchase a ticket. If both conditions are met, the contract adds the player's address to a map of players and decrements the number of available tickets. If the player has sent more tez than the cost of a ticket, the extra balance is sent back to the player.

The end_game entry point is used by the contract owner to end the game. Before ending the game, the contract checks if all tickets have been purchased. If so, a winner is picked by generating a random number and selecting a player from the map of players. The winner's address is used to send the entire balance of the contract as a reward. After the reward is sent, the game is reset.

A test scenario is also provided that tests the functionality of the contract. The test scenario includes both valid and invalid test cases for the buy_ticket and end_game entry points.

![Lottert_dapp pic](https://user-images.githubusercontent.com/84145371/221544063-779b1357-e4f4-466d-aa5f-b3dfd928d146.jpg)

This project Deployed on Ghostnet Testnet.
