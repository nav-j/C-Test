# 🧑‍💻 C For Loop Tasks (Task + Solution + Output)

---


## 🟢 Task : Sum of First N Numbers

### 🎯 Task

Find sum of first N natural numbers.

### ✅ Solution

```c id="m5h2g2"
#include <stdio.h>

int main() {
    int n, i, sum = 0;

    printf("Enter N: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++) {
        sum += i;
    }

    printf("Sum = %d", sum);

    return 0;
}
```

### 💻 Output

```
Enter N: 5
Sum = 15
```

---

## 🟠 Task 5: Prime Number Check

### 🎯 Task

Check whether a number is prime.

### ✅ Solution

```c id="5hv1gx"
#include <stdio.h>

int main() {
    int num, i, isPrime = 1;

    printf("Enter number: ");
    scanf("%d", &num);

    if(num <= 1)
        isPrime = 0;

    for(i = 2; i <= num / 2; i++) {
        if(num % i == 0) {
            isPrime = 0;
            break;
        }
    }

    if(isPrime)
        printf("Prime number");
    else
        printf("Not a prime number");

    return 0;
}
```

### 💻 Output

```
Enter number: 7
Prime number
```

---

## 🔴 Task 6: Pattern Printing (Stars)

### 🎯 Task

Print the following pattern:

```
*
**
***
****
*****
```

### ✅ Solution

```c id="96bbnh"
#include <stdio.h>

int main() {
    int i, j;

    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
    }

    return 0;
}
```

### 💻 Output

```
*
**
***
****
*****
```

---
