Assignment 2 and Midterm 2 topics
Collapse
For the second assignment and midterm, you will work in groups of three again. Please let others know here if you need a team. Once you have a team, choose one of you to email me your names and I will set up a Blackboard group in the Groups section for you.

Please choose from among the following topics, or message me if you have an idea of your own you would like to work on. The topics are first-come, first served in order of reply to this discussion. Instructions for Assignment 2 are in the Assignments and Tests section. Instructions for Midterm 2 presentations will also be the same format as Midterm 1 the week after completing Assignment 2.

1. design an approximate Convex Hull algorithm by working in polar coordinates

2. compare the rumtime efficiecy of at least two different mathematics programming APIs for computing matrix inverse
  * stick with matrix sizes of 5 by 5
  * limit the entries to be in the range [-10, 10]
  * you could very likely get an approximate measure for the percentage of matrices it is possible to invert at the same time as your experiments

3. write a report on the different mathematics programming APIs that are available
  * at least one to start with is C++ Boost library

4. design your own combination of balanced tree and array data structure
  * have the array be a staging area of memory---used as temporary first place to store a constant number of elements inserted
  * use the tree to back up elements for longer-term storage
  * how does your data structure compare to an API library balanced tree in the same langauge?

5. write a report on skip list data structure

6. program the two different Gaussian elimination algorithms
  * compare between the second version with more accurate treatment of floating-point operations, the limitations of the first version with specific examples of where it fails and yet the second is able to successfully continue execution

7. implement a naive graph colouring algorithm (does not need to find the minimal number of colours)
  * program with a GUI to visualize the colouring(s)

8. implement topological sort for directed acyclic graphs
  * focus debugging up to about 8 vertices

9. implement a visualization of the rounds of the Josephus problem for up to input of size 100
  * keep in mind that the problem describes people participating in a circle

10. write a report on the data structures designed for optimal indexing in databases
  * focus on the one that you research to be the most performant, and include a few of what you find are the most performant if you cannot determine otherwise

11. implement a "multiplication" operation between two input graphs
  * implement your own graph data structure
    * add nodes
    * connect nodes
  * implement connections with linked-lists (use a library API for the lists)
  * Wolfram Mathworld: Graph Cartesian Product
    * https://mathworld.wolfram.com/GraphCartesianProduct.html
    * focus on the statement cited as from Harary, 1994, and this is easiest to create a new graph with the vertices described and edges between them

12. implement breadth-first search
  * implement your own graph data structure
    * add nodes
    * connect nodes
  * implement connections with linked-lists (use a library API for the lists)
  * just use an array to implement the queue you will need while performing BFS
    * how much memory will the queue need, in general, for input graph with n nodes?

13. visualize for random input of a set of 2D points, say 30 in an input collection, the last recursive merge for efficient closest pair of points
  * because recursion would have solved each half (left 15, right 15) for their closest pair of points, program the easier brute force version and apply it to both halves
  * then draw the boxes involved that prove how the more efficient merge operation finds the full collection's closest pair
