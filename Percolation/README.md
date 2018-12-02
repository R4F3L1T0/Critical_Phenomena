# Percolation

Assume that some liquid is poured on top of some porous material. Will the liquid be able to make its way from hole to hole and reach the bottom?  
This physical question is modelled mathematically as a three-dimensional network of *n × n × n* vertices, usually called "sites", in which the edge or "bonds" between each two neighbors may be open (allowing the liquid through) with probability *p*, or closed with probability 1–*p*, and they are assumed to be independent. Therefore, for a given *p*, what is the probability that an open path (meaning a path, each of whose links is an "open" bond) exists from the top to the bottom? The behavior for large n is of primary interest. This problem, called now bond percolation, was introduced in the mathematics literature by Broadbent & Hammersley (1957),and has been studied intensively by mathematicians and physicists since then.  
In this repository I solve numerically by Monte Carlo techniques the Percolation problem in 2D (the algorithm is easily extendable to any number od dimensions).  

g++ -std=c++11 swendsen_wang.cpp to run the code.
