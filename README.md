# Watopoly

![Watopoly gameplay in the terminal](Watopoly.png)

Watopoly was a CS246 project at the University of Waterloo in Winter 2023. The
course provided the game concept, board, and rules. Our three-person team built
the C++14 terminal version and worked out how to organize it.

## The game

Two to six players move around a 40-square campus board, buying academic
buildings, residences, and gyms. They can auction, trade, improve, and mortgage
properties, then save a game to pick up later. The last player who hasn't
declared bankruptcy wins.

## How we built it

We kept the game rules with the board, players, and squares. The controller
handles commands and turns; response objects carry results back to the player.
The text display observes changes so the board updates as players move and
buildings gain improvements. Our design changed during the project, and the
final design document explains those decisions.

## Explore the project

- [Project page](https://ryanmaxin.github.io/watopoly-public/) — an introduction to the game and our work
- [Final design document](https://ryanmaxin.github.io/watopoly-public/design.pdf) — our architecture and design decisions
- [Final UML diagram](https://ryanmaxin.github.io/watopoly-public/uml-final.pdf) — the class structure

We share the screenshot and design documents publicly. The implementation is
kept out of the public repository under course academic integrity rules.

## Team

- [Ryan Maxin](https://github.com/Ryanmaxin)
- [Isha Chaudhry](https://github.com/Ishac1)
- [Nandish Patel](https://github.com/nandishofficial)
