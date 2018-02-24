# Snap-Blackjack

### Goal of the Game

Drawing random cards from Ace (1) to Jack (11) by clicking on the Card image, the player is supposed to stop choosing cards (click on the stop sign) at or before 21. Or else, the player loses.
___

### Instructions / How to Start with the given xml

Before starting, make sure that students are familiar with
+ how changing costumes work
+ control blocks
+ conditional statements (if, else)
+ declaring variables and keeping track of them

### Steps
## In the Card Sprite
1. Declare variables `Total` and `Current card`
2. Set `Current card` to a random number between 1 and 11
3. Switch the costume to the variable `Current card` to switch the card that corresponds to the random number stored in `Current card`
4. Check if `Total` is greater than 21. If so, set `Total` and `Current card` to 0, display "You lose" as a display message, and switch costume to 0
## In the stop sign
1. Check if `Total` is less than 21. IF so, display "You win" as a display message. Else display "You lose"
