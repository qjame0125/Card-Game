# Card-Game
A card game brings together multiple important concepts—from implementing shuffle algorithms and search techniques to designing object- oriented class structures and managing game state. You'll create a command-line application where players can compete against a computer opponent. 

# Blackjack Python Game
About Game

This is a Blackjack game implemented in Python, where a player plays against a CPU dealer. The goal is to get as close to 21 as possible without going over. The game handles card values, Ace adjustment, and CPU logic.

# Summary of Rules and Logic

The game uses a standard 52-card deck.

Each card has a rank and suit.
# Card values:

Face cards (King, Queen, Jack) = 10 points

Number cards = their numeric value

Ace = 11 points (adjusted to 1 if total > 21)

Player Rules:

Player starts with 2 cards.

Can Hit (draw a card) or Stand (end turn).

Player wins instantly with Blackjack (21 in 2 cards).

Player busts if total exceeds 21.

# Dealer Rules (CPU):

Dealer hits until score ≥ 17.

Dealer adjusts Ace values to avoid busting.

Dealer stands at 17 or higher.

# Winner Determination:

Player wins if they have higher score than dealer without busting.

Dealer wins if player busts or has lower score than dealer.

Tie if both scores are equal.

# How to Run the Game
Open terminal or command prompt in the project folder.

Run the game with:

Follow the prompts:

Press h to Hit (draw a card)

Press s to Stand

# Features Implemented

Full Deck creation with 52 cards.

Card class for rank and suit.

Player class for player and dealer hands.

Card value calculation, including Ace adjustment.

Player vs CPU dealer logic.

Interactive game with Hit/Stand options.

Winner determination at end of round.

Text-based hand and score display.

# Future Features to Implement

Multiple rounds with betting/chips.

Save and load high scores.

Option for multiplayer local game.

# Libraries Used

random → for shuffling the deck and drawing cards.

