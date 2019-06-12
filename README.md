# deny_and_conquer
A real-time distributed multiplayer game supporting concurrency, coordination and fault tolerance. The game board is a square divided into boxes of equal size. The game is played by players, each having a pen of different color. The objective is to deny your opponents filling the most number of boxes, by taking over as many boxes as you can. To take over a box, you must color the box with your pen, and at least X% of the area of the box must be colored to be considered taken over by you. Specifically, a player click anywhere inside the box and hold the click button down, while scribbling inside the box. Otherwise, another player can try taking over the box. Once a box has been taken over by a given player, the box turns entirely to the color of the player and can no longer be taken over by any other player. At the end of the game, when all boxes have been taken over, whoever has the most number of boxes will win the game.


### Running
You need to have redis server running before starting the game. Then:

`npm install`

`npm run start`
