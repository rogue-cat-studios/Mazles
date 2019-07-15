# Mazles

## About this project

This project serves as an issue tracker and support hub for Mazles and **does not** contain source code, at least for the time being. In the future I might decide to make Mazles open source, in which case it will go on my [personal GitHub](https://github.com/poodleslayer), but for the sake of consistency I would like to keep any issues or support topics here :)

## What is Mazles!?

_"Sounds like a disease - plays with ease!"_

![Mazles game board](images/game_board.png)

Mazles is a simple but fun, relaxing yet challenging maze game. Tap on tiles to rotate them in order to connect the Start and Finish tiles. There are a variety of game modes and difficulties for players of all skill levels! Harder difficulties will increase the size of the maze while limiting the types of tiles that are generated, forcing you to be a bit more careful with your path...

- **Arcade Mode** - a series of hand-crafted mazes, this mode will hopefully provide the most interesting challenges. Keeps track of how many tiles you used so you can compare with friends!
- **Speed Demon** - a classic time trials mode with all difficulties, this mode tracks how quickly you solve the mazes. This mode consists of **procedurally generated mazes** and therefore may be prone to some issues. If you get stuck, just start a new round!
- **Perfectionist** - this mode tracks how many moves it takes to solve a maze, so careful planning is key. Pen and paper may be handy in order to think through optimal solutions before making any moves. As with Speed Demon, this mode features **procedurally generated mazes** and may result in some funky mazes.

**Note** - the method for generating mazes in Speed Demon and Perfectionist modes is not perfect. The ideal algorithm would be a self-avoiding random walk, however this is tricky to do fast and also doesn't guarantee there won't be unintended trivial solutions. I will keep messing with the generation in hopes of getting something that will be interesting and also guarantees the maze is solvable. Thanks for being patient!