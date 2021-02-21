
Here is the github containing the edited version of the code found in problem 4 of the screening tasks. 

Despite the very few additions to the code itself I think it performs the required function in the smothest possible way. 

The first change was adding the weight of the edge to the cost function, we can apply a phase change that corresponds to the weight of the edge. 

The second change was adding the weight of the edge to the cost Hamiltonian.

These two changes were easily implemented using the existing code implementation. 

I tested the new method and it seemed to work smoothly. In order to improve the testing I made the graph structure randomized (whilst setting the number of edges and nodes).