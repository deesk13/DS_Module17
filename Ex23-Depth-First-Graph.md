# Ex23 Depth First Graph
## DATE:25-05-25
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
```
Allocate Memory: Use malloc to allocate memory for a new node of type struct node.
Initialize Vertex: Set the vertex field of the new node to the value v.
Initialize Next Pointer: Set the next pointer of the new node to NULL.
Return Node: Return the pointer to the newly created node.
End Function: Complete the function execution.
``` 

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: DEVA DHARSHINI.I
RegisterNumber:212223240026
struct node* createNode(int v) {
  struct node* newNode = malloc(sizeof(struct node));
  newNode->vertex = v;
  newNode->next = NULL;
  return newNode;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/ac700aaa-37c0-4d27-a61e-3f82ee1a8815)


## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
