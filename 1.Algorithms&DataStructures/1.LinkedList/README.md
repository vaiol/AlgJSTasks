### Linked List
Design your implementation of the linked list. 

You can choose to use the singly linked list or the doubly linked list. A node in a singly linked list should have two attributes: val and next. val is the value of the current node, and next is a pointer/reference to the next node. If you want to use the doubly linked list, you will need one more attribute prev to indicate the previous node in the linked list. Assume all nodes in the linked list are 0-indexed.

#### Note:
     
- Please do not use the built-in LinkedList library or Array.
- Your implementation should work with any data type as values, but for test you can use numbers.
- Cover your implementation by Unit Tests (you can use any Library for that).
- You must implement all methods of the class LinkedList.

#### Example:
```JavaScript
const linkedList = new LinkedList();
linkedList.addAtHead(1);
linkedList.addAtTail(3);
linkedList.addAtIndex(1, 2);  // linked list becomes 1->2->3
linkedList.get(1);            // returns 2
linkedList.deleteAtIndex(1);  // now the linked list is 1->3
linkedList.get(1);            // returns 3
linkedList.print();           // prints 1->3
```
