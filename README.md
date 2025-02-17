# Droplet-method
An odd algorithm that might be good for graph traversal


Simple Idea, the specifics for the algorithm should use a node by node dropping.

So looking at the idea it should be a graph, we drop a node and indicate all nodes that have been visited and the spread one level out just as any breath first searches go.
next we move on to another node that has not been hit, and then we drop again, if it touches another node that has already been hit, there exists a path between
