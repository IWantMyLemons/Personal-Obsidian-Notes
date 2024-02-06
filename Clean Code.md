---
share: true
---


Definition:: general tips to keep your code clean

If possible seperate a program into parts
```c
#include <stdbool.h>
#include <stdio.h>

bool is_prime(int x) {
	if (x < 2) return false;
	for (int i = 2; i < x; i++) {
		if (x % i == 0) return false;
	}
	return true;
}

int main() {
	int n;
	scanf("%d", &n);

	if (is_prime(n)) {
		printf("n is prime");
	} else {
		printf("n is not prime");
	}
}
```

---
Related:
- [Example](./Example.md) : An example note

Further Reading:
- [Example](./Example.md)
