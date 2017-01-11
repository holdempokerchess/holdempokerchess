# How to Play Hold'em Poker Chess

Hold'em Poker Chess is basically [Texas Hold'em Poker](https://en.wikipedia.org/wiki/Texas_hold_'em) but with a spatial element inspired by [Chess](https://en.wikipedia.org/wiki/Chess).

The basic differences are:

1. Cards are associated with Chess pieces and inherit the way they *attack* on the grid of cards like the Chessboard grid.
2. You have to attack cards from the center to include them in your hand. The cards don't move once placed though.
3. Whenever you bet you can choose to place one or both of your *hole* cards facedown on the card grid around the center cards to *attack* them and secure your hand (or it could just be a bluff!)
4. It *is* possible to attack your opponents cards and include them in your hand! But you won't know what they are until the showdown (the reveal of cards).
5. At the showdown you make a normal poker hand that includes any hole cards you have left, plus your choice of the cards you *attack* from the center. If you include an *attacked* card, you must also include the *attacking* card, but you can't chain (i.e. include an attacked card of a card you have attacked.) 

These are the basic rules, some explanations and examples should make the rest clear.

1. [Chess Card Attacks](#chess-card-attacks)
2. [Card Placement](#card-placement)

## Chess Card Attacks

An explanation of how each card *attacks*. Often the high poker value cards have powerful chess attacks to match but there are some differences, the *Ace* is the *Bishop* and the *Ten* is the *Rook*. The cards don't move once placed and their attacks aren't blocked by other cards, this means cards that attack the whole center row can be very useful because they give you a lot of options.

### King
![King Attacks](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/king-attacks.png?raw=true)

### Queen
![Queen Attacks](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/queen-attacks.png?raw=true)

### Bishop : Ace
![Ace Attacks](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/bishop-ace-attacks.png?raw=true)

### Knight : Jack
![Knight Attacks](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/jack-knight-attacks.png?raw=true)

### Rook : Ten
![Rook Attacks](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/rook-ten-attacks.png?raw=true)

### Pawn : Two, Three, Four, Five, Six, Seven, Eight, Nine
![Pawn Attacks](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/pawn-attacks.png?raw=true)

## Card Placement

There are a few rules about card placement.

1. You can only place cards *after the flop* (after the first three center cards are dealt). 
2. You can only place cards when it's your turn to bet.
3. You can place one, both or none of your *hole* cards. If you don't place a card you can still call, raise or check as normal.
4. You have to place a card *adjacent* to a card already on the table, so orthogonally or diagonally in the imaginary grid of cards.
5. You can't place a card where it would block the *turn* or the *river* (the last two cards dealt in to the center).
6. Your cards can be placed on either side of the table, but pawns are always assumed to attack towards the center cards.
7. Your cards are placed facedown and are hidden until the showdown, you aren't required to attack any cards as long as the card is placed legally, you can bluff!
8. You have to remember where your placed your cards, you can use tokens to help remember.. but no peeking.

Here is an example of someone's turn after the flop as they decide whether to place any cards.
![Flop Moves](https://github.com/holdempokerchess/holdempokerchess/blob/master/images/flop-moves.png?raw=true)
