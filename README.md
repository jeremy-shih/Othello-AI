To play the Othello game, run with command `python3 othello_gui.py -d [dimension]`, where [dimension] can be placed with the size of the board. Providing a single number is enough since the board is square.

To play against my minimax algorithm agent, run `python3 othello_gui.py -d [dimension] -a agent.py -m".

To play against my alpha-beta algorithm agent, run `python3 othello_gui.py -d [dimension] -a agent.py`.

To play with a depth limit, add a `-l [depth_limit]` at the end of the command. Ex: `python3 othello_gui.py -d [dimension] -a agent.py -m -l [depth limit]`, where you can choose the depth limit.

To play with caching states, add a `-c` at the end. Ex: `python3 othello_gui.py -d [dimension] -a agent.py -m -c`.

To play with node ordering heuristics and caching states, add a `-o` at the end. Ex: `python3 othello_gui.py -d [dimension] -a agent.py -c -o`.

(This project is based on one of Columbia University’s Artificial Intelligence Courses(author: Daniel Bauer))
