# DAY83-TICKTACKTOE
MY TIC-TAC-TOE PROJRCT - DAY 83

Starting this projet, My Biggest Challenge was finding a way to represent the grid for the 

game and after a couple of attempts, I finally came up with a way to represent the grid in the command line and collect inputs to match each portion of the grid.

My Approach 

I Created a Class called Tic-Tac-Toe which has attributes and methods.

Attributes included:

      A list which contained the players inputs in terms of numbers ranging from 1 - 9 where each number represents a position on the game grid

      A dictionary called 'markers' which takes each number in each players list and uses it to create the game grid.

      Flags like "game_over" to check if any player has won, "current_player" to check whose turn it is.

Methods included:

      "start game" which is called at the beginning of the game ensures the player inputs are empty and the current player is assigned as 'x'

      "Print_guide" prints a guided grid which shows the Player which numbers corresponds to which position on the grid.

      "Collect_input" Collects the user Input and ensures the Input is a valid input before Proceeding.

      "Update_markers" This method takes all the items in the each of the Players Input arrays and appends each entry into the position in the grid. for example, if player_1's array is = [1, 5, 9], each item in the list represents a position for player 1 on the grid. Therefore the method writes "x"  into the game grid at position 1, 5, 9. and does the same for player 2 but with "o"

      "update_p1" and "update_p2" are used to add the processed user input into theie individual arrays

      "print_grid" prints all game grid alongside every user's input.

      "check_for-winner" Checks to se if there's a winner.

