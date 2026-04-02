#  C Star Pattern Programs (For Loop)

---

##  Task 1: Right Triangle Star Pattern

###  Task

Print the pattern:

```
*
**
***
****
*****
```

###  Solution

```c
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

###  Output

```
*
**
***
****
*****
```

---

##  Task 2: Inverted Star Pattern

###  Task

Print:

```
*****
****
***
**
*
```

###  Solution

```c
#include <stdio.h>

int main() {
    int i, j;

    for(i = 5; i >= 1; i--) {
        for(j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
    }

    return 0;
}
```

### Output

```
*****
****
***
**
*
```

---

## 🔴 Task 3: Pyramid Star Pattern

### 🎯 Task

Print:

```
    *
   ***
  *****
 *******
*********
```

### ✅ Solution

```c
#include <stdio.h>

int main() {
    int i, j;

    for(i = 1; i <= 5; i++) {

        // spaces
        for(j = 1; j <= 5 - i; j++) {
            printf(" ");
        }

        // stars
        for(j = 1; j <= (2 * i - 1); j++) {
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
   ***
  *****
 *******
*********
```

---

## 🔴 Task 4: Inverted Pyramid

### 🎯 Task

Print:

```
*********
 *******
  *****
   ***
    *
```

### ✅ Solution

```c
#include <stdio.h>

int main() {
    int i, j;

    for(i = 5; i >= 1; i--) {

        // spaces
        for(j = 1; j <= 5 - i; j++) {
            printf(" ");
        }

        // stars
        for(j = 1; j <= (2 * i - 1); j++) {
            printf("*");
        }

        printf("\n");
    }

    return 0;
}
```

### 💻 Output

```
*********
 *******
  *****
   ***
    *
```

---

## 🔥 Task 5: Diamond Pattern

### 🎯 Task

Print:

```
    *
   ***
  *****
 *******
*********
 *******
  *****
   ***
    *
```

### ✅ Solution

```c
#include <stdio.h>

int main() {
    int i, j;

    // upper pyramid
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= 5 - i; j++)
            printf(" ");

        for(j = 1; j <= (2 * i - 1); j++)
            printf("*");

        printf("\n");
    }

    // lower pyramid
    for(i = 4; i >= 1; i--) {
        for(j = 1; j <= 5 - i; j++)
            printf(" ");

        for(j = 1; j <= (2 * i - 1); j++)
            printf("*");

        printf("\n");
    }

    return 0;
}
```

### 💻 Output

```
    *
   ***
  *****
 *******
*********
 *******
  *****
   ***
    *
```

---
