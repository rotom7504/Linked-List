# Linked-List<br>
A linked list is a linear data structure that includes a series of connected nodes. Here, each node stores the data and the address of the next node. For example,<br>
You have to start somewhere, so we give the address of the first node a special name called HEAD. Also, the last node in the linked list can be identified because its next portion points to NULL.<br>
Linked lists can be of multiple types: singly, doubly, and circular linked list. <br>
# Representation of Linked List:- <br>
Each node consists:<br>
<br>
1.A data item<br>
2.An address of another node<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234295252-007e3b02-1878-45bb-8a74-0ca0fc23c172.png)
<br>
The power of a linked list comes from the ability to break the chain and rejoin it. E.g. if you wanted to put an element 4 between 1 and 2, the steps would be:<br>
<br>

1.Create a new struct node and allocate memory to it.<br>
2.Add its data value as 4<br>
3.Point its next pointer to the struct node containing 2 as the data value.<br>
4.Change the next pointer of "1" to the node we just created.<br>
<br>
# Linked List Utility <br>
<br>
*Lists are one of the most popular and efficient data structures, with implementation in every programming language like C, C++, Python, Java, and C#.<br>

*Apart from that, linked lists are a great way to learn how pointers work. By practicing how to manipulate linked lists, you can prepare yourself to learn more advanced data structures like graphs and trees.<br>
<br>
# Complexity:- <br>
<br>
<b><ins> Time Complexity </b></ins><br>
<br>
<img width="455" alt="Linked List Png" src="https://user-images.githubusercontent.com/125802204/234297003-b54653b1-e6af-4ad1-9664-41db6b709d2d.png">
<br>
<br>
<b><ins> Space Complexity:-</b></ins> O(n)<br>
<br>
# Linked List Applications:- <br>
<br>
1.Dynamic memory allocation<br>
2.Implemented in stack and queue<br>
3.In undo functionality of softwares<br>
4.Hash tables, Graphs<br>
<br>
<br>
