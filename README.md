# [Augmented Reality Chess](http://carlosmccosta.github.io/AR-Chess/)

## Overview
AR-Chess is an augmented reality chess GUI implemented using osgART.
It allows users to play chess games against a chess engine or against another human.

## Main features
* Uses Universal Chess Interface (UCI) protocol to communicate with the chess engine (currently uses Stockfish, but any UCI engine can be used)
* Allows 3 different game modes: Human vs Human, Human vs Computer and Computer vs Computer
* Allows going back and forward in the player chess piece moves
* Implements and enforces all chess rules
* Possible moves are shown for the chess piece the player wants to move
* Player isn't allowed to make invalid moves
* All user interaction is done with [2 markers](https://github.com/carlosmccosta/AR-Chess/tree/master/Source/AR-Chess/patterns) (1 for the board and 1 for the selector)

[![AR-Chess demo](https://raw.github.com/carlosmccosta/AR-Chess/master/Screenshots/AR-Chess.png)](http://www.youtube.com/watch?v=id)
AR-Chess GUI


## Releases
[Windows release](https://github.com/carlosmccosta/AR-Chess/tree/master/Releases/Windows)

## Building and developing
The setup instructions on how to build and develop in Visual Studio is available [here](https://github.com/carlosmccosta/AR-Chess/blob/master/Source/Configuration/Visual%20Studio%20configuration.txt)