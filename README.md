# war-card-game
Turing College Python Project:

# War Card Game

## Objective

The goal of the game is to win all the cards by beating your opponent’s card in each round.

## Requirements

- 2 players
- A standard deck of 52 cards, minus Joker

## How to play

1. Shuffle the deck of cards.
2. Deal all the cards evenly, face down.
3. Both players flip the top card simultaneously and place each card face up in the middle of the table.
4. Comparet the values of the cards:
- Aces are highest, followed by King all the ways down to 2 (lowest).
- Suits do not matter.
5. Player with the higher value card takes both cards in the middle and place them face down at the bottom of their deck.
6. "War" occurs when a player card and an opponent card are of equal value:
- Each player takes 3 additional cards from their deck and place them face down in the middle.
- Each player takes another card from their deck and flip it face up.
- Player with the higher value card takes all cards in the middle (original tied cards, 6 additional cards, and the final 2 cards).
- If there's another tie, repeat the process.
7. Win condition is met when one player has all the cards.

## Python code setup

### Card class
- Represents a single card with its suit and value.
### Deck class
- Represents a deck of 52 cards.
### Player class
- Represents a player.
