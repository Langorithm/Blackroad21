# Blackroad 21 ♤♧♡♢

### Intro
v0.1

Point-based card gathering and racing game based in Blackjack 21. This how-to assumes you know the rules to that game.
2 player game? Maybe more??


To play you will need:
* A standard poker deck of 52 cards
* A joker card
* A token representing each player
* Playing knowledge of Blackjack 21

### The board
The game's zones are the following:
* The deck
* The field, composed of a 16 *stops* in a 3 x 3 grid, one of which is the **Start**.
* The finish line, marked by a joker.
* Each player's glove box, which start without cards.
 
Setting it up:

1. Set up the field by laying 3 rows of 3 faced down cards.
2. Pick one of the 4 cards at the corners of the grid, this will be the **Start**. Place the player tokens just beside this start, marking the players to be at this location.
3. Place the joker just beside the card opposite to the **Start**. This marks the **Finish Line**.

### Playing the game

The goal of the game is to get to the finish line by collecting cards and to maximize their score by the end. Players race through the field by taking turns to move their tokens around the stops and playing hands of Blackroad (similar to a hand of Blackjack) at each stop.

>##### A hand of Blackroad
>
>A hand of *Blackroad* is played just like a hand of *Blackjack*, with some key differences:
>* There is no concept of a *split* or a *double*.
>* Players have a pool of cards called a **Glovebox**. Instead of drawing a card from the deck, they may take a card from their **Glovebox** and add that to hand's total.
>* *Blackroad* hands are played solo, not against a dealer.
>
   
   


Once you have set up the board, pick the starting player.

1. Flip the card at the **Start** to be face up. Do the same for the two cards adjacent to it.
2. The starting player plays a hand of *Blackroad*, using the card at the start as their first card dealt.
3. Just like in *Blackjack*, the player may decide to stop receiving cards before the hand reaches a sum of 21. 
	* If the sum exceeds 21, they have busted and their entire hand is discarded.
	* If the sum is 21 or less, they take those cards and put it in their **Glovebox**.
	* Also, if the sum is exactly 21, they make take another turn.

It is now the next turn, and the game continues as follows:

4. The acting player moves their piece to their choice of a face up card *adjacent* to their current card.
5. The face-down cards adjacent to the new current card are flipped face up.
6. The player plays a hand of *Blackroad* using the card at their stop as their initial card dealt. Just like before, the initial card on the stop and the cards dealt from the deck for this hand are added to that player's **Glovebox**, provided the hand's total does not exceed 21.
8. Any cards taken from a player's **Glovebox** to add to the hand's sum are not returned to their **Glovebox**, rather, they are placed in the current stop, ready to be used in a future hand of *Blackroad*, should a player position themselves there in the future. This means a stop may have more than one card in it when a player leaves it.
9. If the hand's total was exactly 21 and this is not the second consecutive turn for the player, the player may take a second turn.
10. Otherwise, the player's turn ends. 

Repeat from step 4 until a player reaches the stop marked by the finish line. A final hand is played, and if the player's score is 21 or below, they add the *Joker* to their **Glovebox**, in addition to that hand's cards as usual.

The game ends. Players then total the values of the cards in their toolbox using the same scores for each card as in a hand of the game.
However:
* An ace is worth 1 point, not 11, for the purposes of player scoring.
* The joker is worth 21 points.

The player with the highest **Glovebox** total wins.

### Notes
* Calculate if you can run out of cards
* What to do if you run out of cards?
* Can we raise the number of players?
* Can we raise the size of the field? Probably yes but we'll need to merge two decks. How does this affect the blackjack aspect of the game? 
* Remark: You can pick the value of an Ace, but what is the total value in the end? What about when you reuse the cards?
* Instead of taking another turn, a 21 might grant the option to move diagonally.
* Radical change: Have a larger map and deal the 2/3/4 jokers as cards of the initial field. Kind of like a treasure hunt.
