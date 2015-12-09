---
title: What's the Game of Life?
slug: what-game-of-life
---

In this tutorial you are going to familiarize yourself with Objective-C
and a game development tool called SpriteBuilder by making a mobile
version of Conway's Game of Life. If you've never heard of Conway's Game
of Life,
[Wikipedia](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) has a
great article. Nearly every programmer has written a version of this
game at some point in their careers and wasted lots of time staring at
cool shapes morphing. Consider this your initiation :p


TL;DR
=====

There is a grid of cells. A cell is either alive or dead. If a cell has
less than two live neighbors, it dies. If it has more than three
neighbors, it dies. If a live cell has exactly two or three neighbors,
it stays alive and if a dead cell has exactly three neighbors, it comes
to life. The Wikipedia article has some great examples of common patterns
that produce cool effects. 

You can check out this [online implementation of the Game of Life](http://pmav.eu/stuff/javascript-game-of-life-v3.1.1/?autoplay=0&trail=0&grid=1&colors=1) to get a feel
for how it works.

Try placing a few live cells and then hitting the next button to run one
round. Press the *Animate* button to continuously run
the game, or use *Step* to increment one round at a time. Play around with it a little and come back when you're ready.
We'll wait :)

