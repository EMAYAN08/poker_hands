# poker_hands
Poker is a game which people play with a normal set (or deck) of 52 cards. Poker is a gambling game which involves some luck, but also some skill. In poker, players make bets against each other depending on the value of their poker hand. Bets are usually made with plastic or ceramic discs called chips. Bets may also be made with real money, but chips are more often used because they are easier to handle and count. At the end of the game, players either swap their chips for money, or the chips are counted to determine the order of winners.
In poker, players form sets of five playing cards, called hands, according to the rules of the game. Each hand has a rank, which is compared against the ranks of other hands participating in the showdown to decide who wins the pot.

Objective
Build a machine learning model to predict poker hand.

About the Data
Each record is an example of a hand consisting of five playing cards drawn from a standard deck of 52. Each card is described using two attributes (suit and rank), for a total of 10 predictive attributes. There is one Class attribute that describes the “Poker Hand”.

 

Attribute Information:

   1) S1 - “Suit of card #1”

      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

 

   2) C1 - “Rank of card #1”

      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

 

   3) S2 - “Suit of card #2”

      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

 

   4) C2 - “Rank of card #2”

      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

 

   5) S3 - “Suit of card #3”

      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

 

   6) C3 - “Rank of card #3”

      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

 

   7) S4 - “Suit of card #4”

      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

 

   8) C4 - “Rank of card #4”

      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

 

   9) S5 - “Suit of card #5”

      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

 

   10) C5 - “Rank of card 5”

      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

 

   11) Class - “Poker Hand”

      Ordinal (0-9)

 

      0: Nothing in hand; not a recognized poker hand 

      1: One pair; one pair of equal ranks within five cards

      2: Two pairs; two pairs of equal ranks within five cards

      3: Three of a kind; three equal ranks within five cards

      4: Straight; five cards, sequentially ranked with no gaps

      5: Flush; five cards with the same suit

      6: Full house; pair + different rank three of a kind

      7: Four of a kind; four equal ranks within five cards

      8: Straight flush; straight + flush

      9: Royal flush; {Ace, King, Queen, Jack, Ten} + flush

 
