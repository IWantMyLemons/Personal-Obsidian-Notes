---
share: true
---


Definition:: Putting [Struct](./Struct.md) in another [Struct](./Struct.md)

```c
struct Cat {
	char name[64];
};

struct Person {
	struct Cat pet;
};
```

---
Related:
- [Example](./Example.md) : An example note

Further Reading:
- [Example](./Example.md)
