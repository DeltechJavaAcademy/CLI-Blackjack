<h1>CLI-Blackjack</h1>

You will create a Blackjack game in the command line.

<h2>Part One</h2>
<h3>Requirements</h3>
<ul>
  <li>The system should store the deck as a list of ints from 0-51</li>
  <li>The system should deal two random cards from the deck to both the dealer and player</li>
  <li>The user can view one of the cards the dealer was dealt</li>
  <li>The user can view the two cards they were dealt</li>
  <li>The user can HIT or STAND until they BUST or choose to STAND</li>
  <li>The user receives another card if they choose to HIT</li>
  <li>The system deals the dealer cards until they BUST, cards total 17+, or they beat the players hand</li>
  <li>The user can choose to play again or quit</li>
</ul>
<h3>Mock Ups</h3>

Dealer Hand: A of D
Your Hand: 2 of C, 3 of H

Your Move: HIT

Dealer Hand: A of D
Your Hand: 2 of C, 3 of H, 10 of H

Your Move: HIT

Dealer Hand: A of D
Your Hand: 2 of C, 3 of H, 10 of H, K of S

BUST! Dealer Wins!
Play again (y/n): y

Dealer Hand: K of C
Your Hand: 10 of C, 9 of S

Your Move: STAND

Dealer Hand: A of D, 6 of D, 7 of H
Your Hand: 10 of C, 9 of S

Dealer Bust! You win!
Play again (y/n): n

<h2>Part Two</h2>
<h3>Requirements</h3>
All Part one requirements plus
<ul>
  <li>The system should check for bad user input</li>
  <li>The system should represent Move as an Enum</li>
  <li>The system asks the user to HIT, STAND, DOUBLE, or SPLIT</li>
  <li>The user receives another card if they choose to HIT or DOUBLE</li>
  <li>The user can split if they are dealt two cards of the same rank</li>
  <li>The system splits the user's hand into two hands if they split</li>
  <li>The system should store the deck as a list of Cards</li>
  <li>Bonus: The system should represent a card as a Suit and Rank (Requires Classes)</li>
  <li>Bonus: The system should represent Suit, Rank, and Move as Enums</li>
</ul>
<h3>Mock Ups</h3>

Dealer Hand: A of D
Your Hand: 2 of C, 9 of H

Your Move: DOUBLE

Dealer Hand: A of D
Your Hand: 2 of C, 9 of H, 7 of H

Your Move: STAND

Dealer Hand: K of D, 7 of D
Your Hand: 2 of C, 9 of H, 7 of H

Dealer must Stand! You win!
Play again (y/n): y

Dealer Hand: K of D
Your Hand: 9 of C, 9 of H

Your Move: SPLIT

Dealer Hand: K of D
Your First Hand: 9 of C
Your Second Hand: 9 of H

Your Move: HIT

Dealer Hand: K of D
Your First Hand: 9 of C, J of S
Your Second Hand: 9 of H

Your Move: STAND

Dealer Hand: K of D
Your First Hand: 9 of C, J of S
Your Second Hand: 9 of H, 6 of S

Your Move: HIT

Dealer Hand: K of D
Your First Hand: 9 of C, J of S
Your Second Hand: 9 of H, 6 of S, 9 of S

Your Second Hand Bust!

Dealer Hand: K of D, 7 of D
Your First Hand: 9 of C, J of S
Your Second Hand: 9 of H, 6 of S, 9 of S

Dealer must Stand! You win!
Play again (y/n): n
