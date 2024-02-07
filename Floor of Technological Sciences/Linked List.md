---
share: true
---


Definition:: a way of storing data where elements are grouped with a pointer to the next one 

> each group of data and pointer is called a `Node`

Linked lists can be represented with a polynomial representing the order of the nodes. e.g. $\{5,16,14,21\}$ is $5x^3+16x^2+14x+21$

Circular linked lists happen when you connect the tail to the head
Ouroboros moment

## Singly linked
a singly linked list contains a pointer to the next node
```c
struct IntNode {
	int data;
	struct IntNode* next;
};

// a list holding {3,2,1} should look like
// value   [...][  3][  b][...][  2][  c][...][  3][  0][...]
// address [...][  a][a+1][...][  b][b+1][...][  c][c+1][...]
```

## Doubly linked
a doubly linked list contains a pointer to the next node and previous node
```c
struct IntNode {
	int data;
	struct IntNode* next;
	struct IntNode* prev;
};
```

## Usage
Linked lists are normally used where insertions and deletions happen near the start of the list, though it's speed is debatable due to modern hardware.


---
Related:
- [Example](../Meta/Example.md) : An example note

Further Reading:
- [Example](../Meta/Example.md)
