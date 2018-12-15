# Minesweeper 



Relive your childhood memories playing Minesweeper! This version is simlar to traditional Minesweeper game except the user has the option to "save" game status and undo 
any number of moves. 


- The user can only undo moves after he/she has played any moves, which is true even when the previous 
saved game status is reloaded, i.e, the user cannot undo moves he/she made in that previous round 
(If the game is reloaded with 2 flagged cells from the previous round, the user cannot undo those 2
flagged cells, but can undo the 3rd flagged cell, which would count as the user's first move in this new round). 

- The game status is automatically saved when the user exits out the window, and is given the option of 
whether they want to restore previous status or start a new game when the game is reopened.

-On the Mac, right click is clicking the keypad with 2 fingers.

## Rules of the game: 

The goal is to sweep all the “mines” or bombs from a 16x16 mine field. There are 40 in total. 

To obtain information on where the bomb is, left click to uncover the cells. A cell with a number reveals the number of neighboring cells (the 8 most direct ones surrounding it) containing bombs, although itself will not contain a bomb. A cell that does not contain a bomb in its direct neighbor cells (the 8 most direct ones surrounding it) is an empty cell, and when clicked on, will reveal the entire region of all empty cells until a cell with a number appears. Use this information plus guess work to avoid the bombs. 

To mark a cell you think is a bomb, right-click on the cell and a flag will appear. You have 40 flags in total, one for each bomb. You will be notified when you have used up all your 40 flags with a count of how many flags you have left in the lower left corner. 

The game is won when the user has successfully identified all the cells that contain bombs and the game is lost when the player clicks on a cell which contains a bomb. 

The user can “unflag” a cell by right clicking the cell again. The user can undo any number of moves for any type of move, which includes clicking on flagged cells, empty cells, and neighbor cells. 

To start a new game, the user just clicks anywhere on the board. The user can stop the game at any point by exiting the game. The game will automatically be saved. When re-loaded, the user will have the option of starting a new game or starting from the most recent version of the game when exited. 
