# Python Chess Engine

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [TODO](#todo)
* [Instructions](#instructions)
* [Further development ideas](#further-development-ideas)

## General info
I have been playing chess since my childhood and one day I got an mini-project in my college days to implement chess in Python. Then, I came across a tutorial by Eddie Sharick, who made a whole 16 episodes series covering the topic.
This repository is a result of following his videos,  sometimes coming up with some improvements on my own. Hereby, I highly
encourage you to visit his YouTube channel and check the whole series by yourself.

[Eddie's YouTube channel](https://www.youtube.com/channel/UCaEohRz5bPHywGBwmR18Qww)

[First episode of "Chess engine in Python"](https://www.youtube.com/watch?v=EnYui0e73Rs&ab_channel=EddieSharick)

## Technologies
* Python 3.7.8
* pygame 2.0.1

## TODO
- [ ] Cleaning up the code - right now it is really messy.
- [ ] Using numpy arrays instead of 2d lists.
- [ ] Stalemate on 3 repeated moves or 50 moves without capture/pawn advancement.
- [ ] Menu to select player vs player/computer.
- [ ] Allow dragging pieces.
- [ ] Resolve ambiguating moves (notation).

## IDE Recommended:
- PyCharm

## Instructions
1. Clone this repository.
2. Select whether you want to play versus computer, against another player locally, or watch the game of engine playing against itself by setting appropriate flags in lines 52 and 53 of `ChessMain.py`.
3. Run `ChessMain.py`.
4. Enjoy the game!

#### Sic:
* Press `z` to undo a move.
* Press `r` to reset the game.

## Further development ideas
1. Ordering the moves (ex. looking at checks and/or captures) should make the engine much quicker (because of the alpha-beta pruning).
2. Keeping track of all the possible moves in a given position, so that after a move is made the engine doesn't have to recalculate all the moves.
3. Evaluating kings placement on the board (separate in middle game and in the late game).
4. Book of openings.

## Screenshots



 ![image](https://github.com/Ombhabal/Chess/assets/143935443/409bc39f-8c45-4d1a-8708-3acaaf9c75f3)

 


![image](https://github.com/Ombhabal/Chess/assets/143935443/8a91958d-45d9-4ab9-be39-a292c7315947)




![image](https://github.com/Ombhabal/Chess/assets/143935443/02892d39-88c1-4e23-a97a-2393b727f49a)



  

