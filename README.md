# pacmanAI
Implementation of Minimax, Alpha Beta Pruning, and Expectimax search to control pacman intelligently. 

![Alt Text](http://ai.berkeley.edu/images/pacman_game.gif)

This project is part of the Pac-man projects created by John DeNero and Dan Klein for CS188 at Berkeley EECS.

The file that differs from the original project multiAgents.py. All other files were not created or edited and are only here to for the purpose of viewing my implementation of minimax and expectimax. 

### To run this code
within the main directory, you can run these commands. 
***Note that this code runs with python 2.7, not python 3.X***

(Example command: `python pacman.py -p AlphaBetaAgent -l trappedClassic -a depth=3 -q -n 10`)

#
`python pacman.py` is the base command but pacman will not move without specifying a few options first:


<img src="https://img.shields.io/badge/required--red.svg" alt="Chat"> 

* `-p` specifies the type of agent 
  * ReflexAgent
  * MinimaxAgent
  * AlphaBetaAgent
  * ExpectimaxAgent
  
<img src="https://img.shields.io/badge/optional--blue.svg" alt="Chat"> 
  
* `-l` specifies the map you want pacman to play on
  * testClassic 
  * openClassic 
  * *The full list can be found in the /layouts folder within the main directory*
  
* `-n` specifies the number of times to run the simulation
 
* `-k` specifies the number of ghosts to play against pacman

* `-a` specifies funciton specific options
  * For alpha beta pruning, depth=X tells the function what depth to expand the game decision tree. 
  * For other agents, evalFN=better uses the more complex evaluation function, which is used when smarter searches cant come up with a move. 
  
* `-q` runs the simulation in the background and doesnt show pacmans project with graphics. This is much faster and useful when running hundreds of simulations.

* `--frameTime 0` can be added to run the siulation at a higher speed, while `--frameTime <1 or higher>` will run the simulation prograssively slower the higher the number. 



#   

Running `python autograder.py` grades this assignment, so feel free to see what I got for a grade on this project!



