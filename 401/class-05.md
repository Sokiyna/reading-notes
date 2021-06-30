Linked Lists
List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.
Linked List: A data structure that contains nodes that links/points to the next node in the list.
Singly: refers to the number of references the node has.
Doubly: refers to there being two (double) references within the node.
Node: individual items/links that live in a linked list.
Next: This property contains the reference to the next node.
Head: is a reference of type Node to the first node in a linked list.
Current : Current is a reference of type Node to the node that is currently being looked at.
we are not able to use a foreach or for loop. The best way to approach a traversal is through the use of a while() loop.
If we accidentally end up trying to traverse on a node that is null, a NullReferenceException gets thrown and our program will crash/end.
what exactly is happening through an example:
creating Current at the Head.
We create a while loop.
checking if the value of the current node is equal to the value we are looking for.
If the Current node does not contain the value we are looking for, we then must move Current to the next node that is being referenced.
Once we hit the end, we know that we did not find the value and return true at any point, so the value is not in the LinkedList. We return false.
Traversal Big O
The Big O of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list.
The Big O of space for Includes would be O(1). This is because there is no additional space being used than what is already given to us with the linked list input.
Adding a Node
If we want to add a node with an O(1) efficiency, we have to replace the current Head of the linked list with the new node, without losing the reference to the next node in the list.
ALGORITHM Add(newValue)
// INPUT <– Value to add
// OUTPUT <– No output
newNode <– NEW Node
newNode.Value <– newValue
newNode.Next <– Head
Head <– newNode
Adding a node to the middle of a linked list is a bit different than adding to the beginning. This is because we are working with more nodes and must re-allocate to make room for the new node.
ALGORITHM AddBefore(newValue, valueToAddBefore)
// INPUT <– New value, Value to add before
// OUTPUT <– boolean
Current <– Head
IF Current is equal to NULL
return FALSE
WHILE Current.Next is not equal to NULL
IF Current.Next.Value is equal to valueToAddBefore
  newNode <-- NEW Node
  newNode.Value <-- newValue
  newNode.Next <-- Current.Next
  Current.Next <-- newNode
  return TRUE
Current <-- Current.Next;
return FALSE
What’s a Linked List, Anyway pt1
Linear data structures
There is a sequence and an order to how they are constructed and traversed.
In non-linear data structures, items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.
Trees and graphs are also non-linear data structures that we traverse in different ways.
Just as characters, numbers, words, sentences require bytes of memory to represent them, so do data structures.