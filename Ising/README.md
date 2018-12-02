# Ising Model

The Ising model is a mathematical model of ferromagnetism in Statistical Mechanics. The model consists of discrete variables that represent magnetic dipole moments of atomic spins that can be in one of two states (+1 or −1). The spins are arranged in a graph, usually a lattice, allowing each spin to interact with its neighbors. The model allows the identification of phase transitions, as a simplified model of reality. It is also possible to view the Ising model as a Markov chain. In this work I solved the dynamics of model numerically with the Metropolis algorithm and implementing several simulations to investigate the behaviour of physical systems undergoing phase transitions near their critic points.  
In particular, in this repository, I solve the 2D Ising model (for which exist a very complicated analytical solution too) using the *Swendsen–Wang* algorithm, the first non-local or cluster algorithm for Monte Carlo simulation for large systems near criticality. The algorithm is non-local in the sense that in a single sweep of moves a collective update of the spin variables of the system is done.   

g++ -std=c++11 swendsen_wang.cpp to use it.

