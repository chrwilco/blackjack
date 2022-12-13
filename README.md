# blackjack

This program allows the user to play a game of Blackjack.
There are 10 classes that make up the project.

Player.java:
  This class adds a Player object to the program. It stores the cards the player has, how many chips, and how much is bet by the player.
  
Hand.java
  This class deals the hands to the player and the dealer.
  
Deck.java
  This class make a new object called Deck. This is where the 52 cards are stored and where the cards are dealt from.
  
Dealer.java
  This class makes a new dealer hand object. It calculates the dealers total, shows the player what card is face up, and adds cards to the dealers hand.

Card2.java
  This class makes a Card object. It creaters the 52 cards that are used in the Deck.java object.
  
BlackjackGame.java
  This class plays the actual game. It shuffles the deck, gets the bets, deals the cards, allows the player to hit or stay, plays the dealers hand, calculates the
  winnings, and finishes the hand/game.
  
Blackjack.java
  This is the main class. It will initialize the game and calls the classes to allow the user to play.
  
InvalidDeckPositionException.java
  This class extends the Exception class and allows the program to determine if there is an error in the deck.
  
InvalidCardValueException.java
  This also extends the Exception class and allows the program to determine if the card is not a 2-10 or J,Q,K,A.
  
InvalidCardSuitException.java
  This Exception extension allows the program to determine if the card has an invalid suit.
