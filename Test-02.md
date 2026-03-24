# C Basics Worksheet

# Questions

## Multiple Choice and Fill in the Blanks

### 1. What is the meaning of comments in C?

* To output text
* To create text variables
* To explain and document code
* To print text and numbers with a simple line of code

### 2. Comments in C are written with special characters. Insert the missing parts:

```c
____ This is a single-line comment
This is a multi-line comment ____
```

### 3. When do we usually use multi-line comments?

* For short comments
* For longer comments
* For comments that should be printed

### 4. Which data type is used to store integers (whole numbers) in C?

* `char`
* `float`
* `int`
* `double`

### 5. What is the correct syntax to declare a variable of type `int` with the value 15?

* `int = 15;`
* `int myNum = 15;`
* `int: myNum = 15;`
* `myNum int = 15;`

### 6. Create a variable named `myNum` and assign the value `50` to it.

```c
____  ________ = ____ ;
```

### 7. Why won't the following code run?

```c
int myNum = 15;
printf(myNum);
```

* `printf` is missing a format specifier
* It will run! It will print 15
* It will run! It will print `myNum`

### 8. Which data type is used to store single characters in C?

* `char`
* `int`
* `float`
* `string`

### 9. What is the correct syntax to declare a float variable named `myFloat` without assigning it a value?

* `float myFloat = ;`
* `myFloat = float;`
* `float myFloat;`
* `myFloat float;`

### 10. True or False:

You can declare a variable in C without assigning it a value and assign the value later.

### 11. What format specifier is used to print an integer value in C?

* `%f`
* `%d`
* `%c`
* `%s`

### 12. Use the correct format specifier to output the value of `myNum`:

```c
int myNum = 15;
printf("____", myNum);
```

### 13. Which format specifier would you use to print a floating-point number?

* `%d`
* `%f`
* `%c`
* `%i`

### 14. What will the following code output?

```c
int myNum = 15;
printf("%d", myNum);
```

* 15
* `%d`
* `myNum`
* An error

### 15. Display the sum of `5 + 10`, using two variables: `x` and `y`.

```c
______  _______  = ______ ;
int y = 10;
printf("%d", x + y);
```

### 16. Which format specifier is used to print a single character in C?

* `%d`
* `%f`
* `%c`
* `%s`

### 17. True or False:

You can print a value directly in `printf()` without using a variable, as long as the correct format specifier is used.

### 18. What happens when you assign a new value to an existing variable in C?

* The previous value is overwritten
* The previous value is deleted, and the variable is cleared
* The new value is ignored
* An error occurs

### 19. What will the following code output?

```c
int myNum = 15;
myNum = 10;
printf("%d", myNum);
```

* 15
* 10
* `%d`
* An error

### 20. What will the following code output?

```c
int myNum = 15;
int myOtherNum = 23;
myNum = myOtherNum;
printf("%d", myNum);
```

* 15
* 23
* `myOtherNum`
* An error

### 21. Which of the following lines correctly assigns the value of one variable to another?

* `myNum == myOtherNum;`
* `myOtherNum = myNum;`
* `myNum = 15 == myOtherNum;`

### 22. What will the following code output?

```c
int x = 5;
int y = 6;
int sum = x + y;
printf("%d", sum);
```

* 5
* 6
* 11
* An error

### 23. How do you declare multiple variables of the same type in C?

* Separate each variable with a semicolon
* Use a comma-separated list
* Declare each variable on a new line
* Use square brackets around variable names

### 24. Fill in the missing parts to create three variables of the same type, using a comma-separated list:

```c
_____ myNum1 = 10__ myNum2 = 15__ myNum3 = 25;
printf("%d", myNum1 + myNum2 + myNum3);
```

### 25. What will the following code output?

```c
int x = 5, y = 6, z = 50;
printf("%d", x + y + z);
```

* 5
* 6
* 5650
* 50
* 61

### 26. What does the following code do?

```c
int x, y, z;
x = y = z = 50;
```

* Assigns 50 to x, y, and z
* Assigns different values to each variable
* Declares variables without assigning values
* Throws an error

### 27. How would you declare three integer variables `a`, `b`, and `c` with values `1`, `2`, and `3` in a single line?

* `int a 1, b 2, c 3;`
* `int a = 1; int b = 2; int c = 3;`
* `int a = 1, b = 2, c = 3;`
* `int a, b, c = 1, 2, 3;`

### 28. What will the following code output?

```c
int x, y, z;
x = y = z = 20;
printf("%d", x + y + z);
```

* 20
* 40
* 60
* An error

---

## Theory Question

### Q-1. What are operators in C? Explain in detail all types of operators.

---

# Answer Key

## Objective Answers

**1.** To explain and document code
**2.**

```c
// This is a single-line comment
/* This is a multi-line comment */
```

**3.** For longer comments
**4.** `int`
**5.** `int myNum = 15;`
**6.**

```c
int myNum = 50;
```

**7.** `printf` is missing a format specifier
**8.** `char`
**9.** `float myFloat;`
**10.** True
**11.** `%d`
**12.**

```c
printf("%d", myNum);
```

**13.** `%f`
**14.** `15`
**15.**

```c
int x = 5;
int y = 10;
printf("%d", x + y);
```

**16.** `%c`
**17.** True
**18.** The previous value is overwritten
**19.** `10`
**20.** `23`
**21.** `myOtherNum = myNum;`
**22.** `11`
**23.** Use a comma-separated list
**24.**

```c
int myNum1 = 10, myNum2 = 15, myNum3 = 25;
printf("%d", myNum1 + myNum2 + myNum3);
```

**25.** `61`
**26.** Assigns 50 to x, y, and z
**27.** `int a = 1, b = 2, c = 3;`
**28.** `60`

---

## Theory Answer

### What are operators in C?

Operators in C are special symbols used to perform operations on variables and values. They are used in expressions to carry out tasks like addition, comparison, logical checking, assignment, and more.

### Types of Operators in C

#### 1. Arithmetic Operators

Used to perform mathematical operations.

* `+` Addition
* `-` Subtraction
* `*` Multiplication
* `/` Division
* `%` Modulus

Example:

```c
int a = 10, b = 5;
printf("%d", a + b);
```

#### 2. Relational Operators

Used to compare two values.

* `==` Equal to
* `!=` Not equal to
* `>` Greater than
* `<` Less than
* `>=` Greater than or equal to
* `<=` Less than or equal to

Example:

```c
if (a > b)
```

#### 3. Logical Operators

Used to combine conditions.

* `&&` Logical AND
* `||` Logical OR
* `!` Logical NOT

Example:

```c
if (a > 0 && b > 0)
```

#### 4. Assignment Operators

Used to assign values to variables.

* `=` Assign
* `+=` Add and assign
* `-=` Subtract and assign
* `*=` Multiply and assign
* `/=` Divide and assign
* `%=` Modulus and assign

Example:

```c
x += 5;
```

#### 5. Increment and Decrement Operators

Used to increase or decrease a variable by 1.

* `++` Increment
* `--` Decrement

Example:

```c
x++;
y--;
```

#### 6. Bitwise Operators

Used to perform operations on bits.

* `&` Bitwise AND
* `|` Bitwise OR
* `^` Bitwise XOR
* `~` Bitwise NOT
* `<<` Left shift
* `>>` Right shift

#### 7. Conditional (Ternary) Operator

A shorthand form of `if-else`.

* `? :`

Example:

```c
int max = (a > b) ? a : b;
```

#### 8. Special Operators

These include operators like:

* `sizeof` – returns size of a variable
* `&` – address of variable
* `*` – pointer operator
* `.` – access structure member
* `->` – access structure member through pointer

### Conclusion

Operators are very important in C because they help perform calculations, comparisons, decisions, and value assignments. Without operators, writing programs would not be possible.
