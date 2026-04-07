

##  Task 1: Print numbers from 1 to 10

###  Problem:

Write a program to print numbers from 1 to 10 using a `while` loop.

###  Solution:

```c
#include <stdio.h>

int main() {
    int i = 1;

    while(i <= 10) {
        printf("%d\n", i);
        i++;
    }

    return 0;
}
```

###  Output:

```
1
2
3
4
5
6
7
8
9
10
```

---

##  Task 2: Print even numbers from 1 to 20

###  Problem:

Print all even numbers between 1 and 20.

###  Solution:

```c
#include <stdio.h>

int main() {
    int i = 2;

    while(i <= 20) {
        printf("%d\n", i);
        i += 2;
    }

    return 0;
}
```

###  Output:

```
2
4
6
8
10
12
14
16
18
20
```

---

##  Task 3: Find sum of first N natural numbers

###  Problem:

Take a number `N` from the user and find the sum from 1 to N.

###  Solution:

```c
#include <stdio.h>

int main() {
    int n, i = 1, sum = 0;

    printf("Enter a number: ");
    scanf("%d", &n);

    while(i <= n) {
        sum += i;
        i++;
    }

    printf("Sum = %d", sum);

    return 0;
}
```

###  Sample Output:

```
Enter a number: 5
Sum = 15
```

---

##  Task 4: Reverse a number

###  Problem:

Reverse a number entered by the user.

###  Solution:

```c
#include <stdio.h>

int main() {
    int num, reverse = 0, rem;

    printf("Enter a number: ");
    scanf("%d", &num);

    while(num != 0) {
        rem = num % 10;
        reverse = reverse * 10 + rem;
        num /= 10;
    }

    printf("Reversed Number = %d", reverse);

    return 0;
}
```

###  Sample Output:

```
Enter a number: 123
Reversed Number = 321
```

---

##  Task 5: Check palindrome number

###  Problem:

Check whether a number is a palindrome (same forward and backward).

###  Solution:

```c
#include <stdio.h>

int main() {
    int num, original, reverse = 0, rem;

    printf("Enter a number: ");
    scanf("%d", &num);

    original = num;

    while(num != 0) {
        rem = num % 10;
        reverse = reverse * 10 + rem;
        num /= 10;
    }

    if(original == reverse)
        printf("Palindrome Number");
    else
        printf("Not a Palindrome");

    return 0;
}
```

###  Sample Output:

```
Enter a number: 121
Palindrome Number
```

---

##  Task 6: Count digits in a number

###  Problem:

Count how many digits are in a number.

###  Solution:

```c
#include <stdio.h>

int main() {
    int num, count = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    while(num != 0) {
        num /= 10;
        count++;
    }

    printf("Number of digits = %d", count);

    return 0;
}
```

### 📌 Sample Output:

```
Enter a number: 4567
Number of digits = 4
```

---

If you want, I can also create:
✅ **Practice worksheet (no solutions)**
✅ **MCQs on while loop**
✅ **Pattern-based while loop questions (stars, numbers)**
Just tell me 👍
