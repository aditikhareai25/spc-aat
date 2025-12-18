# spc-aat
CASINO SIMULATOR
This simulator mimics the core loop of a real-world casino game: the buy-in, the wager, the house edge, and the payout. It provides a safe environment to explore how probability and bankroll management work in software development.
Core Mechanics:
The Bankroll: The player starts with a fixed "wallet" of 1,000 units. The game persists as long as the player remains solvent.
The Odds: Since the player picks 1 number out of 10, the mathematical probability of winning is $10\%$.
The Payout Structure: To keep the game exciting, the simulator offers a 5-to-1 payout. While the odds are 1 in 10, the reward is $5 \times$ the bet, which introduces a "house edge" typical of casino algorithms.
Randomization Engine: Using srand(time(NULL)), the program ensures that the "dealer" (the CPU) isn't predictable, simulating the randomness of a slot machine or a roulette wheel.
