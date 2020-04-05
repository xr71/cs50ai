# Search

### Breadth First Search
May exhaust more paths
Could take longer but may find a more optimal solution



### Depth First Search
May get lucky and find a shorter solution or sooner solution without exploring every path  
But it may not find the most optimal solution all the time


### Uninformed vs Informed
Uninformed means that we do not use any problem specific knowledge in order to search
But often, with human intuition, we know how to improve the search process given the domain

Informed search, for example, means to take a split in the fork that is geographically closer to the goal state (maze)

### Greedy Best First Search
Instead of expanding deepest or shallowest nodes, expand the node that it thinks is closest to the goal
Knowledge of what is close to the goal is a heuristic estimation, h(n)
We can approximate this function using Manhattan Distance


### A\* (A Star) Search
g(n) h(n)
heuristics plus costs
AStar is optimal if h(n) is admissable and h(n) is consistent for every node 


### Adversarial Search
minimax - deterministic games of 2 players
assign utility to outcomes
  - 1 wins
  - 2 wins
  - nobody wins

[-1, 0, 1]

 
