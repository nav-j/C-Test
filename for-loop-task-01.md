Here’s a simple and useful **C programming task using a `for` loop** 👇

---

## 🧑‍💻 Task: Print Multiplication Table

### 🎯 Objective

Write a C program that takes a number from the user and prints its multiplication table up to 10 using a `for` loop.

---

### 📌 Requirements

* Take an integer input from the user
* Use a `for` loop
* Print the table from 1 to 10

---

### 💻 Sample Output

```
Enter a number: 5

5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50
```

---

### ✅ Solution Code

```c
#include <stdio.h>

int main() {
    int num, i;

    printf("Enter a number: ");
    scanf("%d", &num);

    for(i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }

    return 0;
}
```

---

### 🚀 Bonus Challenge

Modify the program to:

* Print tables from 1 to 5
* Or print table in reverse order (10 to 1)

---

If you want, I can create **more practice tasks (easy → advanced)** using `for`, `while`, or patterns 👍
