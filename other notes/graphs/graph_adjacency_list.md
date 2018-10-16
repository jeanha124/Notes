# Learning Goals:

- Give a high level overview of an Adjacency List
- What benefits do we get from an Adjacency List?


Each node has a row - Storing all connections
row = 1D array
## what is stored in the row? 
- [0][0] = no edge beginning
- [0][1] = there is a node and an edge
### row index = start point
### col index = end point

### 1 = edge exists
### 0 = edge does not exist

## Graph Representation
<!-- 0  1  2  3  4  5  6  7 -->
[
 0 [0, 1, 1, 1, 0, 0, 0, 0],
 1 [1, 0, 0, 0, 1, 1, 0, 0],
 2 [1, 0, 0, 0, 0, 0, 1, 0],
 3 [1, 0, 0, 0, 0, 0, 0, 1],
 4 [0, 1, 0, 0, 0, 0, 0, 1],
 5 [0, 1, 0, 0, 0, 0, 0, 1],
 6 [0, 0, 1, 0, 0, 0, 0, 1],
 7 [0, 0, 0, 1, 1, 1, 1, 0]
]

[
 0 [1, 2, 3],
 1 [0, 4, 5],
 2 [0, 6],
 3 [0, 7],
 4 [1, 7],
 5 [1, 7],
 6 [2, 7],
 7 [3, 6, 4, 5]
]

