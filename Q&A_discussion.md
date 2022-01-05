

1. What are ADT's
2. What are the two types of Data Structures --> Linear / Non Linear


Questions for Professor :

1. How does the negative indexing in arrays / tuples / lists work ?
ex. if a[-1] is accessed, then last elemnet is accessed or second element from the last is accessed?
2. Stack can be called as both FILO and LIFO
![image](https://user-images.githubusercontent.com/90809823/146708344-aa3206d9-b7d1-4cb8-a52b-46966a382502.png)
How does this work ?

3. Stacks acan be implemented either using arrays or Linked lists. In case of arrays, when element is inserted/deleted ( pushed/popped), it is done at the end of the array. Whereas in case of linked list, element inserted/deleted is at the beginning of the linked list
4.  ![image](https://user-images.githubusercontent.com/90809823/147175376-21a640c5-7edf-456d-aec2-ac5e9f964788.png)
Operations means push and pop ?

5. ![image](https://user-images.githubusercontent.com/90809823/147271568-ea17f7f5-ea57-43c2-aa94-aa2b9fb6c7bd.png)
6. Stacks can store individual items in its cells or even a word/a double or triple digit number in its cells
 ![image](https://user-images.githubusercontent.com/90809823/147512497-7efe9f50-de4b-4648-8011-5da589796907.png)
 7. When pushing numbers to Stack, use stack.append(1), there is no keyword like .push,  for strings you may use stack.append('a')
 8. In the Stack implementation using arrays, when an element from stack is removed, it is removed from the right end of the stack, Whereas in Queue implementation using arrays, an element is deleted from the beginning
 9. ![image](https://user-images.githubusercontent.com/90809823/147526520-997f5ed7-51fc-4191-914a-95970ca6fada.png)
 10. ![image](https://user-images.githubusercontent.com/90809823/147526551-94a2850f-ef1c-48a3-9b69-44e27aa79791.png)
 11. ![image](https://user-images.githubusercontent.com/90809823/147623284-52870742-91d9-4a87-bda2-6f5cf2e24ad1.png)
 if the element is inserted at the right side or you can call it append function, the first element is still 45 right? then deletion is from right to left direction ? 
 Even in Linked representation of Queues, the element at the left side is removed, whereas if we observe here, the first element in the queue appears to be 5
 ![image](https://user-images.githubusercontent.com/90809823/147623450-7fd77c05-db7b-49ee-8f9f-652109b2ef33.png)
 Answer to this : The first element to be inserted in both array case and LL case are 12 & 9, hence 12 and 9 are the first elements that are removed from the queue , First in First Out ?
 12. ![image](https://user-images.githubusercontent.com/90809823/147623704-5de27b5f-45c7-44d5-9c96-49cb26e22ff7.png)
This is wrong ? This is stack because a is inserted first and c is the last one to be inserted and c is the first element to be popped out. In queues, a must be removed first right ?
13. Queue - PUSH - Append , POP - predelete
14. Stack - PUSH - Prepend, POP - predelete
15. ![image](https://user-images.githubusercontent.com/90809823/147625524-a1fddb24-a734-4d14-af9c-d955ac9d4952.png)
Dequeues are implemented using circular doubly linked list
16. ![image](https://user-images.githubusercontent.com/90809823/147898351-7c929f10-3d32-475a-9c82-48f721fa3fe3.png)
17. Trees are Non-linear data structures. In Pre-order traversal, root node is accessed first, then the left subtree is accesssed with left nodes in sequence followed by right nodes in sequence, and then at the end right sub tree is accesses, even here left nodes are accessed first and then right nodes are accessed. If there are no nodes in its left branch, then the right nodes are accessed before moving on to the next left node ? 
18. Pre-Order- ![image](https://user-images.githubusercontent.com/90809823/147992419-a5222d53-4671-45b3-b23e-a01d795fc7d2.png)
Why is there a repetition of node D while accessing ? ![image](https://user-images.githubusercontent.com/90809823/147992453-334d4220-9df1-494f-b7a5-04934b32bb4e.png)
19. In-Order- For the above problem, my solution is B, D, A, E, H, C, G, F, I. Actual solution is : ![image](https://user-images.githubusercontent.com/90809823/147993455-68108bc9-2500-4437-abd4-22d4f5b38afb.png)
Even in the right sub-tree, same rule of in-order traversal, first left, second root and then right node should be accessed right ? Order of F and I are also interchanged?
20. ![image](https://user-images.githubusercontent.com/90809823/147994087-8b92da89-2bc5-40fa-967e-fac58974d4e4.png)
Pre - Order : 50, 17, 12, 9, 14, 23, 72, 54, 67, 76
In - Order : 9, 12, 14, 17, 23, 50, 54, 67, 72, 76
Post - Order : 9, 14, 23, 17, 67, 54, 76, 72, 50
Are these correct ?
21. ![image](https://user-images.githubusercontent.com/90809823/148093853-84fd438a-462a-4f83-8251-964fe84e78d3.png)
Unlike case 2 where only if one child is present, replace it with node to be deleted and remove the desired node. In case 3 as seen in above picture, replace the node to be deleted with the largest value in its left sub-tree. In this process, when you replace the nodes, the child node is itself repeated in both the parent's position and it's position.
22. ![image](https://user-images.githubusercontent.com/90809823/148095227-eac2172f-7cc6-44e7-9bd5-0b2846332c9e.png)
for this tree, ![image](https://user-images.githubusercontent.com/90809823/148095328-986e9971-b04c-417d-836c-c064e623c5f7.png) , the no. of nodes in right subtrees is 5 right? It is not left sub-trees
23. ![image](https://user-images.githubusercontent.com/90809823/148101282-bcdeb8df-2b07-434a-9573-f0f39e07ecd7.png)
24. ![image](https://user-images.githubusercontent.com/90809823/148248230-51849cae-0736-4158-b5dd-d1788ad58ff5.png)
the balance factor is calculated as total number of nodes in its left subtree - total number of nodes in its right subtree. In the second figure, for node 36, nodes in its left subtrees are 27 & 30, and nodes in its right sub tree are 39?
25. ![image](https://user-images.githubusercontent.com/90809823/148259659-986b57cb-15a5-4a4e-87b7-21d4df7adea9.png)
Before inserting 18, the balance factor of 45 is 1 right, why is it given -1 here ?
26. Rotations for Insertion :
    LL Rotation - (a) If the new node is inserted in the left sub tree of a node 
                  (b) If the left sub tree is heavy
                  
    RR Rotation - (a) If the new node is inserted in the right sub tree of a node 
                  (b) If the right sub tree is heavy
                  
    LR Rotation - If the node is inserted in the right node of a left sub tree
    
    RL Rotation  If the node is inserted in the left node of a right sub tree

27. ![image](https://user-images.githubusercontent.com/90809823/148269324-f0cafdf9-cc67-4376-8f3c-af5a066cc69f.png)
    The balance factor of node 45 is not 0, it is 1. In AVL trees, the nodes in the left subtress are considered if there are nno children in its other sub trees. 


