Reinforcement Learning
Tingfeng Wan        5110757176

1. Value Iteration
   use Bellman update to find Q-Value, then iterate upon it using
   (value iteration) to find the best action for each state
2. Bridge Crossing Analysis
   removing noise to make agent prefer high reward 
3. Policies
   a)no discount with low living reward to encourage close reward
   b)discounted reward to discourage excess steps
   c)no noise and living reward to encourage far reward
   d)discounted reward to discourage excess steps 
   e)positive living reward to encourage non-termination
4-5.skipped
6.Q-Learning
   Using action with best q-value, but with probability of epsilon
   to take a random action, update the q_value from the initial
   trivial policy (q-learning is off-policy)
7.Epsilon Greedy
   implemented in 6
8.Bridge Crossing Revisited
   50 iteration is too short to find the optimal policy
9.Q-Learning and Pacman
   Q-learning was successfully applied onto pac-man
10.Approximate Q-Learning
   Use weight * feature vector to find the q value, and update
   weights using the difference between old and new q value 
Time Spent: ~7-8 Hours