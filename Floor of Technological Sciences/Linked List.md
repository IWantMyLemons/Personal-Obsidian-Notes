---
share: true
---


Definition:: a way of storing data where elements are grouped with a pointer to the next one 

> each group of data and pointer is called a `Node`

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

---
Related:
- [Example](../Meta/Example.md) : An example note

Further Reading:
- [Example](../Meta/Example.md)
