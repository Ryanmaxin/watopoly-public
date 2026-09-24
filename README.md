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

We split the program into game logic, turn handling, and a text display. The
board, players, and squares hold the state and rules. A controller reads commands
and keeps turns moving, while response objects pass the outcome of each action
back to the player. The display observes changes to the players and squares so
it can update the board as the game goes on.

Our design changed as we worked through the project. The final design document
covers the decisions we made and the parts we rethought along the way; the UML
shows where the classes ended up.

## Documents

- [CS246 Watopoly project brief](https://github.com/Ryanmaxin/watopoly-public/blob/main/Watopoly.pdf) — the assignment we worked from
- [Final design document](https://github.com/Ryanmaxin/watopoly-public/blob/main/design.pdf) — our write-up of the implementation and design choices
- [Final UML diagram](https://github.com/Ryanmaxin/watopoly-public/blob/main/uml-final.pdf) — the class structure

We can't share the source publicly because of course academic integrity rules.

## Team

- [Ryan Maxin](https://github.com/Ryanmaxin)
- [Isha Chaudhry](https://github.com/Ishac1)
- [Nandish Patel](https://github.com/nandishofficial)
