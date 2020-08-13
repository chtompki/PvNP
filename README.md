# PvNP

### Claim.

`P != NP` <=> `2^|N| = c`

### Proof

1. __`P = NP` <= `2^|N| != c`.__ Use the infinite binary tree as a representation of `[0,1] \contained-in R`, and construct an infinite SAT polynomial using the Thue-Morse sequence using self similarity to show that P != NP.
2. __`P != NP` => `2^|N| = c`.__ A natral proof by contradiction is to consider the Cantor set and to show it's logical equivalence with the Godel Constructible Universe. We then develop a continuuim based turing machine on such a set and show how P = NP in this arena by solving the SAT polynomial constructed in 1.

