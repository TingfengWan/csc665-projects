Multi-Agent Pac-Man
Tingfeng Wan        5110757176

Reflex Agent: Head towards the nearest food, unless the next move brings Pac-Man next to a ghost
Minimax: use the same function for both Pac-Man and Ghosts, and giving each agent an action before repeating.
    same logic as given in class:
        Pac-Man maximizes the next action
        Ghost minimizes the next action
Alpha-Beta: same logic as Minimax, but included alpha and beta value to use for pruning
Expectimax: Minimax logic, but Ghost performs an average next action
Evaluation Function: 
    using manhattan distance from
        ghost (proximity to scared ghost is REALLY good, otherwise bad, limited to an extent),
        food (position closest to any food is best),
        and capsule (position closest to any capsule is best)
    to evaluate heuristic for any position
