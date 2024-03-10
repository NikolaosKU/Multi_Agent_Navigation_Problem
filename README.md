# Multi_Agent_Navigation_Problem

Navigation and travelling problem to solve the Pac-Man maze (optimally in one case). The game involves multiple instances with just one agent (Pac Man) or more than two agents (Pac-Man and Ghosts)

In both cases, the scope is to use popular supervised and unsupervised algorithms in order to:

- pac-man agent stays alive as much time as possible before gets 'eaten' by the ghosts
- pac-man agent tries to eat as many fruits (rewards) as possible before gets eaten
- pac-man agent shoots for the minimim disctance between current position and fruit based on 'manhatan distance' or 'euclideian distance'
- Pac-man gets rational using heuristics
  
Popular algorithms that were used for the game are:

- CSP (constraint satisfacation problems)
- Decison trees
- Local search
- Markov Decision Processes (MDP)
- SAT solvers
- A* algorithm

..

Please note that when there are too many Ghost-Agents chasing pac-man and 'game over' is inevitable, time clocks against Pac-Man in each step. In this case, Pac-Man will opt-out to be 'eaten' as fast as possible. In plain logic, Pac-Man will direct itself straigh ahead to the closest ghost. This is relevant to 'gamma' concept and the reward function. 

The code was implemented soleldy using Java and Python. The code that is present here is a small part of the total problem.

The code is not my propoerty. Part of the code was provided by the team of the course FAI of KUL computer science department.

Warm regards, Nikos
