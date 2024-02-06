---
share: true
---


Definition:: Custom type to hold data in a structured way

e.g.
```c
struct tdata {
	int age;
	char name[128];
	float score;
};
```

```rust
struct Cat {
	age: u32,
	speed: f64,
}
```

In C(and most other languages), you can access the members of a struct using a `.`:
```c
struct tdata x;

x.age = -5;
strcpy(x.name, "cat");
x.score = 3.14159
```

C/C++ allows you to use `->` to directly access members from a pointer to struct:
```c
struct tdata* ptr_x;

float PI = ptr_x->score;
printf("%s", ptr_x->name);
```

---
Related:
- [Example](./Example.md) : An example note

Further Reading:
- [Example](./Example.md)
