#In-class-lab-exercise-In20-S4-CS2023-Assignment
Index: 200395P

Question 01

In this implementation, I have defined a class Stack that contains an array arr of integers and a variable top to keep track of the index of the top element in the stack. We have also defined the functions push, pop, isEmpty, isFull, stackTop, and display that correspond to the operations performed on a stack.

In the push function, I check if the stack is full, and if not, we increment the top variable and insert the element at the top of the stack. In the pop function, we check if the stack is empty, and if not, we remove the element at the top of the stack and decrement the top variable.

The isEmpty and isFull functions check if the stack is empty or full, respectively. The stackTop function returns the element at the top of the stack without removing it. Finally, the display function prints all the elements in the stack, starting from the top.

Question 02

The code provided is an implementation of a Stack data structure using a singly linked list in C++. The linked list is composed of a series of nodes, where each node contains an integer value and a pointer to the next node in the list.

The Stack class provides functions for adding and removing elements from the top of the stack, checking if the stack is empty, returning the top element, and displaying the contents of the stack. The push() function adds a new node to the beginning of the list to represent the new element being added to the stack. The pop() function removes the head node from the list to represent the top element being removed from the stack. The isEmpty() function checks if the head pointer is null to determine if the stack is empty. The isFull() function always returns false since linked list implementation of the stack does not have a fixed size. The stackTop() function returns the value of the head node to represent the top element without removing it. The display() function prints the contents of the list starting from the head node.

Question 03

Although arrays don't need space for pointers and may be accessed randomly, they are inefficient for memory allocation and insertion/deletion operations. Linked lists, on the other hand, are dynamic and have less time complexity for insertion and deletion. Nevertheless, linked lists take longer to search through, and pointers use more memory per list entry.



