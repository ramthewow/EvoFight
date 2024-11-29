# EvoFight - A text-based bot fighting game using the Genetic Algorithm

This project is a demonstration of Genetic algorithms, an optimisation model based on the nature of biological evolution. 
The bots are governed by a genetic algorithm, which evolves their behavior over multiple generations. Each bot's actions (e.g., punch, kick, block) are influenced by their set of attack probabilities
of punching, blocking or kicking, collectively called a 'genome', which can mutate or crossover with other bots' genomes during the evolution process. 
The goal is to simulate combat and observe how the bots' strategies evolve over time.

### Features:
* Combat system: Players can choose from various attacks (punch, kick, block, and special attack)
* The implementation of genetic algorithm ensures that over time, crossover and mutations will allow the bots to evolve and make the fights challenging
* Bots evolve over multiple generations, with the best-performing bots passing their strategies on to the next generation


### Usage:
Simply run ````fighting_game.py````. Make sure you have Python3 installed.


### Genetic Algorithm functions:
* Crossover: Two parent bots are selected based on their performance (fitness), and their attack probabilities are averaged to create a child bot
* Mutation: The genome of the child bot can undergo small random changes to ensure diversity in the bot population
* Fitness: Every bot is evaluated based on a fitness function, which decides the probability of being selected for crossover
* Evolution: After each generation, the bots that performed well (based on their fitness) are selected to create the next generation. This process repeats for a user defined number of generations.


### Contribution:
Feel free to fork this project and submit pull requests if you have improvements or new features to contribute. If you find any bugs or have suggestions, please open an issue.
