# Tic Tac Toe
The objective of this project is to design and implement the game of Tic Tac Toe using Java. It is a two player game, and the rules are as follows:
  1. The game begins with an empty, 3 × 3 grid.
  2. The two players then take turns placing a mark in an empty grid cell. Player O will use the ‘O’ (letter ‘O’, not zero)        mark and Player X will use the ‘X’ mark.
  3. The game is over in either case: (i) one player has 3 marks in a sequence (vertically, horizontally, diagonally, or anti-      diagonally), or (ii) there are no empty cells left.
  Belowing is a run of the game, where Player O moved first and won the game by placing 3 ‘O’s in the second row of the game grid.
![readmeinsert](https://user-images.githubusercontent.com/28494510/49324249-05fab180-f4df-11e8-97bb-bd9cfc6c3e89.png)

In this game we can add players (up to 100) by username, family name and given name, remove one or all players, modify the name of a player, reset the statistics of one or all players, display the information of one or all players, and rank the players based on winning history.

# Command syntax:
Player management: 
  1. Add a player: addplayer username,family_name,given_name
  2. Remove a player: removeplayer [username]
  3. Rmove all palyers: removeplayer
  4. Edit a player: editplayer username,new_family_name,new_given_name
  5. Reset player statistics: resetstats [username]
  6. Reset all players' statistics: resetstats
  7. Display a player: displayplayer [username]
  8. Display all players: displayplayer
      The output syntax for a player is: username,family_name,given_name,games_played,games_won,games_drawn
  9. Display player rankings: rankings
  
Game play:
  1. Play a game: playgame username1,username2
  2. Make a move: [ ] [ ] 
     (Note: Here a player’s move is represented by two integers in the range of {0, 1, 2} × {0, 1, 2}, where “0 0” represents
      the top-left cell and “2 2” represents the bottom-right cell.)
  3. Exit the game: exit   
