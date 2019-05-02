### Linked List
Design your implementation of the linked list. 

You can choose to use the singly linked list or the doubly linked list. You must be able to defend your choice.

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
