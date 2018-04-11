# pacmanAI
Implementation of both Minimax and Expectimax search to control pacman intelligently. 

![Alt Text](http://ai.berkeley.edu/images/pacman_game.gif)

This project is part of the Pac-man projects created by John DeNero and Dan Klein for CS188 at Berkeley EECS.

The file that differs from the original project multiAgents.py. All other files were not created or edited and are only here to for the purpose of viewing my implementation of minimax and expectimax. 

### To run this code
within the main directory, you can run these commands. 
***Note that this code runs with python 2.7, not python 3.X***

`python pacman.py` is the base command but pacman will not move without specifying a few options first:

<img src="https://img.shields.io/badge/required--red.svg" alt="Chat"> 
* `-p` specifies the type of agent 
  * ReflexAgent
  * MinimaxAgent
  * AlphaBetaAgent
  * ExpectimaxAgent
  
  
  
* `-l` specifies the map you want pacman to play on
  * testClassic 
  * openClassic 

python pacman.py -p MinimaxAgent -l minimaxClassic -a depth=4
python pacman.py -p MinimaxAgent -l trappedClassic -a depth=3
python pacman.py -p AlphaBetaAgent -a depth=3 -l smallClassic
python pacman.py -p AlphaBetaAgent -l trappedClassic -a depth=3 -q -n 10
python pacman.py -p ExpectimaxAgent -l trappedClassic -a depth=3 -q -n 10
python pacman.py -l smallClassic -p ExpectimaxAgent -a evalFn=better -q -n 10


#   

This 



