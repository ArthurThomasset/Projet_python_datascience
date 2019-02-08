# Projet_python_datascience

### Nom du Dataset : Poker hand Dataset

### Contexte :

Chaque observation est un exemple d'une main regroupant 5 cartes tirées d'un paquets de carte standard de 52 cartes.
Chaque carte est décrit suivant 2 attributs : sa suite et son rang. On a donc 10 attributs/variables concernant la main et une autre variable/target qui décrit le main complète.

### Objectif :

Prédire le type de main d'un joueur en connaissant ses cartes.

### Répartition des données : 

25010 en training et 1,000,000 en testing

10 variables et 1 classe target

### Informations sur les variables

   1) S1 : Suit of card #1
      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

   2) C1 : Rank of card #1
      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

   3) S2 : Suit of card #2
      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

   4) C2 : Rank of card #2
      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

   5) S3 : Suit of card #3
      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

   6) C3 : Rank of card #3
      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

   7) S4 : Suit of card #4
      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

   8) C4 : Rank of card #4
      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

   9) S5 : Suit of card #5
      Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

   10) C5 : Rank of card #5
      Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

   11) CLASS Poker Hand : Ordinal (0-9)
   
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
