# eng-puzzles
## ECE4600 G15 2021/2022 Capstone Project Code & Design Files
**As prepared by: Rowen Guncheon, Nicolas Hince, David Stewart, Lin Zhan on March 18/2022**

# AllPaths:
Algorithm used for generating a library of paths from a given input maze.  (For use with future machine learning work)

## MazeSolverMain9.py:
Inputs a black and white photo of a maze orientated bottom(start) to top(finish) in 70:50 pixel size and uses a random weighted backtracking algorithm to output random succesful paths as list of list of coordinates. 

**Library Requirements**
- random 
- numpy
- pandas
- pygame
- csv

## csv2Panda.py:
Inputs csv files of accelerometer data and positioning data and outputs organized Panda dataframes

**Library Requirements**
- pickle 
- numpy
- pandas
- csv

### Requires:
- Python V3.7
