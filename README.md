# SLR-Parser

G:
E -> E + T | T
T -> T F | F
F -> F \* | a | b

The input to the program is a given context-free grammar and a string(your choice). Outputs reverse of the
right most derivation of the string from the given grammar.
a. Computation of LR (0) Sets of Items.
b. Computation of SLR parsing table.
c. Simulation of SLR parser on the given string.
