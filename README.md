# Flips

A two-player card game in a single HTML page: each player gets 10 face-down cards, and the best five-card poker hand wins.

**Play:** open `index.html` in any browser (or via GitHub Pages).

## Rules
- The starting player flips until their best hand beats the other player's (one card does it at the start). Then the other player flips until they beat that, and so on. Ties don't count.
- If you run out of cards without beating your opponent, they lead, but they must still flip all their remaining cards.
- **2s are wild** (optional): a 2 becomes whatever card makes your best hand, including five of a kind.
- **A♠ is instant loss** (optional): flip it and you lose. You must always play your best hand, so if that hand needs a wild to be the A♠ (e.g. a spade royal flush), you lose too.

Hand ranking: Five of a Kind > Straight Flush > Four of a Kind > Full House > Flush > Straight > Three of a Kind > Two Pair > Pair > High Card.
