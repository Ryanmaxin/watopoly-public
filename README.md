# Watopoly

![Watopoly's board in the terminal](Watopoly.png)

We built the C++14 terminal version of Watopoly for CS246 at the University of
Waterloo in Winter 2023. The course gave us the project brief: a campus-themed
Monopoly game with its own board and rules. Our job was to turn that brief into
a working game.

## The game

Two to six players move around a 40-square board filled with Waterloo buildings
and landmarks. Academic buildings, residences, and gyms can be owned; other
squares have their own effects. Players can buy properties or send them to
auction, collect tuition, trade with each other, improve buildings, and mortgage
properties when money gets tight. Games can be saved and loaded, and the last
player who hasn't declared bankruptcy wins.

The image above is a game in progress. A player has landed on PAS and is being
asked whether to buy it or put it up for auction.

## How we built it

We used a Model-View-Controller (MVC)-inspired structure. The board, players,
and squares hold the game state and rules; the controller reads commands and
keeps turns moving; and the text display shows what is happening. Response
objects carry the outcome of each action back to the controller and player.
We used the Observer pattern to update the display when players move or squares
change, and inheritance and polymorphism for the different kinds of squares.

Our design changed as we worked through the project. The final design document
covers the decisions we made and the parts we rethought along the way; the UML
shows where the classes ended up.

## Documents

- [CS246 Watopoly project brief](https://ryanmaxin.github.io/watopoly-public/Watopoly.pdf) — the assignment we worked from
- [Final design document](https://ryanmaxin.github.io/watopoly-public/design.pdf) — our write-up of the implementation and design choices
- [Final UML diagram](https://ryanmaxin.github.io/watopoly-public/uml-final.pdf) — the class structure

We keep the source out of the public repository because of course academic
integrity rules, but we can share it privately on request.

## Team

- [Ryan Maxin](https://github.com/Ryanmaxin)
- [Isha Chaudhry](https://github.com/Ishac1)
- [Nandish Patel](https://github.com/nandishofficial)
