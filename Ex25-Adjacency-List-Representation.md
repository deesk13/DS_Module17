# Ex25 Adjacency List Representation
## DATE:25-05-25
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
```
1.Initialize variables:

Declare n and i as integers.
Read the number of vertices:

Use scanf to read the value of N (number of vertices).
Use scanf to read the value of n (number of edges).
Input edges of the graph:

2.Declare an array edges of type struct Edge with size n.
For each edge i from 0 to n-1:
Use scanf to read the source vertex edges[i].src.
Use scanf to read the destination vertex edges[i].dest.
Construct the graph:

3.Call createGraph(edges, n) to create a graph from the given edges and store the result in graph.
Print the graph:

4.Call printGraph(graph) to print the adjacency list representation of the graph.
End the program:

5.Return 0 to indicate successful completion.
```
## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: DEVA DHARSHINI.I
RegisterNumber:212223240026
int main(void)
{   int n,i;
    scanf("%d",&N);
    scanf("%d",&n);
    // input array containing edges of the graph (as per the above diagram)
    // (x, y) pair in the array represents an edge from x to y
    struct Edge edges[n];
    for (i = 0; i < n; i++)
    {
        // get the source and destination vertex
        scanf("%d",&edges[i].src);
        scanf("%d",&edges[i].dest);
      
    }
   
    // construct a graph from the given edges
    struct Graph *graph = createGraph(edges, n);
 
    // Function to print adjacency list representation of a graph
    printGraph(graph);
 
    return 0;
}

*/
```

## Output:
![image](https://github.com/user-attachments/assets/2da231b1-8c15-4983-bbaa-df3497f58696)



## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
