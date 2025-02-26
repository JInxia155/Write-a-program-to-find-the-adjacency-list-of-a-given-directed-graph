
Download Link : https://programming.engineering/product/questions-write-a-program-to-find-the-adjacency-list-of-a-given-directed-graph/


# Write-a-program-to-find-the-adjacency-list-of-a-given-directed-graph
 🔍 QUESTIONS (Write a program to find the adjacency list of a given directed graph) QUESTIONS (Write a program to find the adjacency list of a given directed graph)


    Write a program to find the adjacency list of a given directed graph G which is represented as

adjacency matrix.

Input Format:

    The first line of the input contains a positive integer n, the number of vertices in the graph, in the range 1 to 1000.

    The next lines represents the Adjacency matrix representation of the given graph.

Output Format:

Then lines contain the adjacency list of each node in ascending order. Each line contains the label of the respective node followed by the nodes adjacent to it sorted in ascending order from left to right separated by single space. If a node has no adjacent nodes, then the line corresponding to its adjacency list will contain

the label of that node only.

Sample Input:

5

01001

00100

00000

00100

00010

Sample Output:

014

12

23

    3

32

    3

    You are given a connected undirected graph G. Write a program for Breadth First Traversal (BFS) of the graph. Find the BFS traversal of the graph starting from the 0th vertex from left to right according to the graph.

Input Format:

    First line consists of V, the number of vertices in the graph, in the range 1 to 1000.

    The subsequent n lines contains the label of the respective node followed by the nodes adjacent to it in ascending order.

Output Format:

    The corresponding Depth First traversal.

Sample Input 1:

5

0123

10

204

30

    2

Sample Output 1:

2

Scanned with CamScanner

Sample Input 2:

4

013

102

30

Sample Output 2:

0132

    You are given a connected undirected graph G. Write a program for Depth First Traversal (DFS) of the graph. You can use a recursive approach to find the DFS traversal of the graph starting from the Oth vertex from left to right according to the graph.

Input Format:

    First line consists of V, the number of vertices in the graph, in the range 1 to 1000.

    The subsequent n lines contains the label of the respective node followed by the nodes adjacent to it in ascending order.

Output Format:

    The corresponding Depth First traversal.

Sample Input 1:

0123

10

204

30

42

Sample Output 1:

01243

Sample Input 2:

4

013

102

21

30

Sample Output 2:

    Write a program to compute the minimum spanning tree of a connected undirected graph G using

the following algorithms:

(a) Kruskal’s algorithm

(b) Prim’s algorithm

Input Format:

    First line contains a character from { ‘a‘, ‘b‘}:

If the input character is ‘a‘ then compute the minimum spanning tree using Kruskal’s algorithm

3

Scanned with CamScanner

Else if the character is ‘b‘ compute the minimum spanning tree using Prim’s algorithm

    Second line contains an integer n Є [1, 1000], that denotes the number of vertices in the graph.

    The subsequent n lines contain the label of the respective node followed by the nodes adjacent to it sorted in ascending order from left to right separated by single space.

    The subsequent n lines contain label of the respective node followed by the weights of the edges corresponding to the adjacency list separated by single space. The edge weights are real numbers in the range [-10000, 10000].

Further, no two edges have the same weight.

Output Format:

    Single line containing the sum of the edge weights of the minimum spanning tree.

Sample Input 1:

a

7

015

1026

213

3246

    356

504

6134

02810

1281614

21612

3122218

4222524

51025

Sample Output 1:

99

Sample Input 2:

b

7

015

1026

213

3246

    3 5 6

504

6134

02810

1281614

21612

3122218

4222524

51025

6141824

Sample Output 2:

99

    Write a program that implements Dijkstra’s algorithm for computing shortest paths in a directed

graph with positive edge weights. Assume that the nodes are labeled from 0 to n –

    1.

4

Input Format:

    The first line of the input contains a positive integer n = [1, 1000], the number of nodes in the graph.

    The subsequent n lines contain the label of the respective node followed by the nodes adjacent to it, sorted in ascending order from left to right separated by single space. If a node has no adjacent nodes, then the line corresponding to its adjacency list will contain the label of that node only.

    The subsequent n lines contain label of the respective node followed by the weights of the edges corresponding to the adjacency list separated by single space. The edge weights are positive real numbers in the range (0, 10000]. If a node has no adjacent nodes, then the line corresponding to its adjacent edge weights will contain the label of that node only.

    The rest of the input consists of multiple lines, each one containing a four–letter string followed by zero, one or two integers. The integers, if given, will be in the range 0 to n–1.

unreachable from the source vertex.

–

The string “apsp“ is followed by a single integer, the label of the source vertex.

Print the shortest path distance from the source vertex to all the n vertices in the graph,

sorted in the order of their labels, in single space separated format. Print “INF“ for

nodes that are

The string “sssp“ is followed by two integers, respectively, labels of the source and des- tination nodes. Print the shortest path from the source node to the destination node, if such a path exists. Print “UNREACHABLE“, otherwise.

The string “stop“ means terminate the program.

Output Format:

The output, if any, of each command should be printed on a separate line.

9

014

15

23

    6

4

5278

62

74

857

0220

    3

27

    5

4

5164

60

72

    21

apsp

0

sssp 07

sssp 5 6

sssp 8 7

sssp 40

stop

LO

5

Scanned with CamScanner

02613125 18109

18

10

13

1

UNREACHABLE

Note: For further queries contact

SEEMA seema_p210047cs@nitc.ac.in

Scanned with CamScanner
