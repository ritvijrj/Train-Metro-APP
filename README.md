# Train-Metro-APP
This is a simple Java program that takes information (name) about the source station and destination station of Delhi Metro from the user and displays the fare and the shortest metro route to reach the destination. It will also have a metro map for better navigation of commuters.

The idea is implemented using Graph and Heap data structures.

The graph has nodes and edges. Nodes represent a metro station that will be containing certain information regarding that station like its name, its metro corridor, and the lines which it connects. Edges (the connection between two nodes) represent the distance between the two stations and the cost of each edge will be equal to the distance between the two of its connecting stations(nodes).

By using different algorithms like Dijkstra, breadth-first search, depth-first search, etc, the shortest path between the source station and the destination station is determined, and accordingly, the fare is being calculated on the basis of the total distance between the two stations. Finally, the metro route between the two stations and the total fare is displayed.

A heap is a special data structure in Java. A heap is a tree-based data structure and can be classified as a complete binary tree. All the nodes of the heap are arranged in a specific order.
In the heap data structure, the root node is compared with its children and arranged according to the order. 

Requirements:
1.Any online or offline Integrated Development Environment (IDE) like Eclipse, Netbeans, ideone.com, etc.
2.Elementary knowledge of Java Programming language to work on the project. Knowledge of data structures like Graph and Heap and Algorithms like Dijkstra, BFS, DFS, etc.
