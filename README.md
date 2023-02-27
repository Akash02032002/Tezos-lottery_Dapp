# Tezos-lottery_Dapp

 <<< UR-HACKTHON >>>

This is a lottery dapp written in smartpy.

This is a SmartPy contract that implements a lottery game. It has two entry points: buy_ticket and end_game.

The buy_ticket entry point is used by players to purchase lottery tickets. Before buying a ticket, the contract checks if there are still tickets available to purchase and if the player has sent enough amount of tez to purchase a ticket. If both conditions are met, the contract adds the player's address to a map of players and decrements the number of available tickets. If the player has sent more tez than the cost of a ticket, the extra balance is sent back to the player.

The end_game entry point is used by the contract owner to end the game. Before ending the game, the contract checks if all tickets have been purchased. If so, a winner is picked by generating a random number and selecting a player from the map of players. The winner's address is used to send the entire balance of the contract as a reward. After the reward is sent, the game is reset.

A test scenario is also provided that tests the functionality of the contract. The test scenario includes both valid and invalid test cases for the buy_ticket and end_game entry points.





This project Deployed on Ghostnet Testnet.

https://tezos-lottery-dapp.vercel.app/  just click on this link and see deployed on Vercel web.

https://vercel.com/aksahkumar02032002-gmailcom/tezos-lottery-dapp

This Project is solved the problem of cheating and fraud in Lottery System.
By its Decentralised in Nature. After bidding is over,The Winning Amount of Tezos-lottery Cryptocurrency will automatically transferred to the randomly choosen User's Account. Due to Smart Contract written in Smartpy and deployed on Ghostnet Blockchain network. Which is 100% Secure.




STEP-1>

To run this project use command these command after installing

git clone https://github.com/Akash02032002/Tezos-lottery_Dapp.git

npm install

![vs code](https://user-images.githubusercontent.com/84145371/221572296-8677379a-ccc8-4e83-bb31-cf42ff9aa89c.jpg)


STEP-2>


npm run dev 


![llottery](https://user-images.githubusercontent.com/84145371/221572346-69c3a917-23ca-4b88-aba4-63e5024b080b.jpg)



STEP-3>


CONNECT THE WALLET WITH TEMPLE WALLET.


![Temple wallet](https://user-images.githubusercontent.com/84145371/221572433-119a9f2b-bfae-46c1-a3ce-0734187a52c2.jpg)


STEP-4>


START BUYING TICKETS.


![Lottert_dapp pic](https://user-images.githubusercontent.com/84145371/221544063-779b1357-e4f4-466d-aa5f-b3dfd928d146.jpg)


https://www.youtube.com/watch?v=_lT1MF-rHDc


CONGRATULATION YOU HAVE SUCCESSFULLY DEBUG A DAPP WHICH IS BUILD ON TEZOS ENVIRONMENT.


HAPPY LEARNING........


