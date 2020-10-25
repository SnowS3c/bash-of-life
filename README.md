# Bash Of Life

## Description

**Conway's Game of Life bash version!**  
## 1. About

A [Game of Life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) simulator written in Bash.

> The Game of Life is a cellular automaton devised by the British mathematician John Horton Conway in 1970.
> 
> The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, _alive_ or _dead_. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
> 
> 1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
> 2. Any live cell with two or three live neighbours lives on to the next generation.
> 3. Any live cell with more than three live neighbours dies, as if by overcrowding.
> 4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
> 
> The initial pattern constitutes the _seed_ of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a _tick_ (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.

## 2. Demo
<p align="center">
  <img src="https://user-images.githubusercontent.com/73076414/97121787-2a8a5300-1721-11eb-97c4-13272fd00b21.gif">
</p>

## 3. Config
You can config the number of rows, columns and initial cells editing ```bash-of-life.sh``` file and setting ```num_rows```, ```num_cols``` and ```num_cells```
```
#!/usr/bin/env bash
#===============================================================================
#  GLOBAL VARIABLES
#===============================================================================
num_rows=20
num_cols=40
num_cells=200
```
