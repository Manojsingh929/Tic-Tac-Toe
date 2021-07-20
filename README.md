# P1-Tic-Tac-Toe
This is my first project.
This is the game of tic tac toe coded in C language.
It is a PvP game with a simple interface.
This is the project on popular Tic-Tac-Toe Game. This game is fairly simple by itself. 
In this game, there is a board with n x n squares. In this project, it is 3 x 3 board. It is a two player game. One of the player chooses ‘O’ and the other ‘X’ to mark their respective cells.  
The moves are chosen by both the players alternatively. First player who fill its three same symbols in a row - horizontally, vertically or diagonally - on a 3 x 3 grid, wins the game. If no one wins, then the game is said to be draw. 
 Step - 1.  Create a 3x3 board using array globally.

Step – 2.  Create a funtion to display the 3x3 board after each insertion of ‘X’ or‘O’.

Step – 3. Create a funtion to checkout the result.
3.1 If  any column or row is filled with one symbol either ‘O’ or ‘X’.then  return 1. Else return 0.
3.2  If any box is empty then return -1.


Step – 4.  In main funtion, create a variable to store player information,to input data from the player and for iteration.

Step – 5. Create a do while loop
5.1 Display the board by calling the function in step-2.
5.2 Select the player with the help of a conditional statement.
5.3 Input the choice from the player 
5.4	If the space is empty on the board, insert his respective symbol. Else print invalid move.
5.5 Call the function in step 3, if it returns 1 or 0, then get out of the loop and go to step 5. if it returns -1,then switch to another player and go to step 4.
(store each returned value to i)
Step – 5. If  i = 1,declare winner, if i=0, print the game is draw.

END  OF THE PROGRAM

