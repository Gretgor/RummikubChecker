# RummikubChecker
A Python implementation of a checking algorithm for arbitrary lists of Rummikub pieces

======= Description of Problem:
=
- Input: a list of simple Rummikub tiles.
- Output: True if the list can be broken down into valid combinations without any pieces left out, False otherwise.

== Rummikub pieces:
=
Each Rummikub piece consists of two pieces of information: 
- A number, between 1 and 13.
- A color, between red 1, blue 2, yellow 3, and black 4.

Each piece is represented by an ordered pair (number, color) in the program.

There is an extra special piece, which will be represented by (0,0), which is a wild card.

== Valid combinations:
=
- Sequences: sequences of consecutive numbers of the same color, comprised of at least three pieces.
- Tuples: tuples of pieces of the same number but different colors, comprised of at least three pieces.

WILD CARDS: a wild card piece can be used at most once per sequence or tuple, replacing exactly one (but any) missing piece.
