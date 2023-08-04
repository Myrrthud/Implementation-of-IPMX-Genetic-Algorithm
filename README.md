# Implementation-of-IPMX-Genetic-Algorithm

*Algorithm For IPMX*

Algorithm 3 Pseudocode of the IPMX.

1: Randomly select two cut points, cp1 and cp2, on parent chromosomes, parent1 and parent2.

2: Produce primitive-offspring1 and primitive-offspring2 by swapping the substrings between cp1 and cp2.

3: Define an exchange list with respect to the chosen substrings.

4: Generate a directed graph of the exchange list.

5: Find all distinct paths between nodes in the graph.

6: For each path that contains more than two nodes, add an edge
between two endpoints and then remove all mid nodes.

7: Update the exchange list, considering the refined paths.

8: Apply the updated exchange list to the primitive-offspring1 to
produce offspring1.

9: Generate F, a list of the same length as the parent chromosomes, initialised to zero.

10: Produce offspring2 by performing the following operations:
(a) F[offspring1[i]] =parent1[i]. (b) offspring2[i] =
F[parent2[i]].
(i = 1, 2, ..., n and n is the length of a parent chromosome)
