# Description

* My project name is Tic-Tac-Toe game.This game is very popular and is fairly simple. In this game,there is a board with n * n squares. In my game,it is 3 * 3 squares. The game can be played by two players. 
                        (1) Player 1           (2) Player 2

* The goal of Tic-Tac-Toe game is to be one of the players to get three same symbols in a row-horizantally,vertically or diagonally on a 3*3 grid.

#Requirements

## High level Requirements
* players should know the rules of the game.
* create a 3 * 3 grid board.
* Declare the winner.

## Low level Requirements
* Knowing the game rules
    i) If any player is able to draw three Xs or three Os in the following combinations then that player wins. The combinations are:
              a)1,2,3                      e)2,5,8
              b)4,5,6                      f)3,6,9
              c)7,8,9                      h)1,5,9
              d)1,4,7                      i)3,5,7
 
 * creating a 3 * 3 grid board
    i)we have to create a 3 * 3 grid board for the game for that I used function board.
    ii) Nine squares were created as we used 3 * 3 grid and we have to name the squares from 1-9.
        
 * Declaring the winner
     i)The player who draw the three Xs or three Os in the above combinations is declared as winner.
     ii)TO check winner I used checkwin function.
