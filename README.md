# Part i)

##  Exploring decentralised approaches to colouring a graph - measuring its success

### Graph topology
Before I could begin with this assignment I had to choose a graph topology. The one I choose was a small world graph.
A small world graph is a graph where the diameter of the graph is limited. This graph had 50 nodes.

### assign_random_colors
This function randomly assigns colors to each of the nodes in the graph. At first each node had four colors to choose
from. 

### count_conflicts
This function loops through the nodes in the graph and its neighbors. If the node and its neighbors has the same color
its increaments the conflicts variable by one. It then returns the conflict variable which is the number of conflicts
in the graph.

### visualize_graph
Takes a colormapping and applies it to the graph allowing the user to draw the graph.

### reduce_conflicts
Iterates through all the conflicts and changes the nodes to a different color.

# Part ii)

## Exploring some aspect of the approach

### reduce_conflicts_priority
The aspect that I decided to explore was priotizes nodes with lower degrees. The degree of a node is the number of neighbors
it has. The idea behind this was that nodes with lower degrees are less likely to create another conflict with another 
neighbor.

