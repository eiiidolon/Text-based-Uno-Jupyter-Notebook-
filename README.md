# jupyter-uno
A text-based multiplayer game inspired by the UNO card game by Hasbro, coded in Jupyter Notebook

**How to Play**
1. Enter the number of players in the game, pick from 2 to 4
2. The game will start from Player 1, on the main menu pick one of two options:
   1: Allows player to see their hand, 
   2: Player will draw a card
3. Upon entering '1', the player will see a list of cards in their hand. Enter the number associated with the card they want to pick (an additional menu may appear/changes to the gameplay may occur if you play an action card, see below in **Action Cards**). If the player wants to return to the main menu, enter '0'
4. Upon entering '2', the player will draw a card and it will be shown on the screen (press Enter/Return to clear). If the card is playable, the player will be prompted on whether they will want to play it, enter Y or N
5. After the player's turn is finished, the screen is cleared and the menu of the following player is shown

**Uno Rules**
- Each player will start off with 7 cards in their hand
- Match your card either by the number/colour/action to the top card of the discard pile or play a Wild/Wild Draw 4 card
- If you do not have any matches or choose not to play any of your cards that match, you need to draw a card. If the drawn card is playable, you may choose whether or not to play it
- The player with no cards remaining in their hand wins

**Action Cards**
Reverse
1. Will reverse the turn order of the game (e.g. If Player 3 plays the reverse card, the following turn will go to Player 2 instead of Player 4)
2. If it is a 2 player game, a Reverse card will skip the next player's turn. 

Skip
1. The next player will have their turn skipped (e.g. If Player 1 played the Skip, Player 2 will skip a turn, Player 3 will play next)

Draw 2
2. The next player will have 2 cards added to their hand and will have their turn skipped (e.g. If Player 1 played the Draw 2, Player 2 will have 2 cards added to their hand and skip a turn, Player 3 will play next)

Wild
1. Upon play a list of colours, enter the number accociated to the colour they want to pick
2. The colour of the card will change accordingly and the game will continue

Wild Draw 4
1. Same procedure as the Wild Card (1 to 2)
2. The next player will have 4 cards added to their hand and will have their turn skipped (e.g. If Player 1 played the Wild Draw 4, Player 2 will have 4 cards added to their hand and skip a turn, Player 3 will play next)

WIP Notes
- Will implement a proper uno-callout system when I figure out how it should work, fow now it is disabled and "Uno!" is printed automatically when a player has 1 card left
- May implement a scoreboard system at the end of the game once a player wins...still thinking about it

Hope you have fun playing my game! :D

