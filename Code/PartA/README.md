Code - Jupyter Notebook for PART A 

We have used Djikstra's Algorithm to solve the PART A problem statement to get the best and optimised route for the delivery, In our Dijkstra's algorithm, the use of a priority queue is crucial for efficiently selecting the vertex with the minimum distance from the source vertex at each step. The time complexity and space complexity of Dijkstra's algorithm with a priority queue depend on the underlying data structure used to implement the priority queue.

Time Complexity:

With a Binary Heap: O((V + E) * log V)
With a Fibonacci Heap: O(V * log V + E)

Space Complexity:

With a Binary Heap: O(V + E)
With a Fibonacci Heap: O(V + E)
Here's a breakdown of the complexities:

Time Complexity:

With a binary heap, the time complexity of each insertion and deletion operation is O(log V). Since there can be at most V vertices and E edges in the graph, and each edge is relaxed at most once, the overall time complexity is O((V + E) * log V).
With a Fibonacci heap, the time complexity of each operation is amortized O(1), which leads to a time complexity of O(V * log V + E).

Space Complexity:
With both binary heap and Fibonacci heap, the space complexity is dominated by the storage of the priority queue and other auxiliary data structures. In the worst-case scenario, where all vertices and edges are present, the space complexity is O(V + E).
