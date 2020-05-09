# Data Structure Notes

## Linked List:

* a 'list' of nodes where each node has a property that points to the next node. The final node will have next as null. The head node starts the list.

* To find the center use two pointers. Start one that increments by two and one by one. When the second pointer finishes the first will be half way through.

```js 
// setup some nodes and connect them to each other
// the linked list looks like:
// (head) n5 -> n4 -> n3 -> n2 -> n1 -> null
const n1 = new Node("Hello", null);   
const n2 = new Node("21", n1); 
const n3 = new Node("Green", n2); 
const n4 = new Node("Blue", n3); 
const n5 = new Node("Daniel", n4); 

// assign a node to the head which functions
// as the entry into our linked list
const head = n5; 

// setup pointers to both start
// at the head of the linked list
let fastPointer = head;
let slowPointer = head;

// loop through the linked list
// when fastPointer reaches the end of the list
// then slowPointer will be at the middle node
while (fastPointer.next !== null && fastPointer.next.next !== null) {
  fastPointer = fastPointer.next.next;   
  slowPointer = slowPointer.next;
}

// slowPointer is now at the middle node in the linked list
slowPointer.data  
```